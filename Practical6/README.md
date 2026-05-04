# 6A-Lab Report: Securing NoSQL Databases (Redis)
**Course:** DBS302 – NoSQL Database Management  
**Practical 6:** Authentication, Encryption (TLS), and RBAC  
**Student Name:** Namgay Wangchuk  

---

## Introduction
The objective of this practical was to implement robust security measures for a Redis database. The main focus was on three primary areas:
1.  **Authentication and RBAC:** Using Access Control Lists (ACL) to define users and restrict their command/key permissions.
2.  **Encryption (TLS):** Configuring SSL/TLS to ensure that all data transmitted between the client and server is encrypted.
3.  **Application Integration:** Verifying the secure setup using a Python-based client.

---

## Part A: Securing Redis

### Step 0: Verification of Initial State
Before applying security configurations, I verified that the Redis server was active and responding to unencrypted, unauthenticated requests. I ran the `ping` command and received a `PONG` response.

```bash
redis-server --version
redis-cli ping
```

> **[Sreenshot 1: Showing redis-cli ping -> PONG]**

![](img/6a-1.png)

---

### Step 1: Implementing Role-Based Access Control (RBAC) via ACL
I modified the `/etc/redis/redis.conf` file to enforce a "Least Privilege" model.

```bash
sudo nano /etc/redis/redis.conf
```

1.  I disabled the **default** user to prevent anonymous access.
2.  I created an **admin** user with full permissions.
3.  I created an **app_user** restricted to keys starting with `session:`.

    ```conf
    # Disable default user
    user default off

    # Admin user: full access
    user admin on >adminStrongPwd ~* +@all

    # App user: session keys only
    user app_user on >appStrongPwd ~session:* +get +set +del +expire +ttl +@connection

    # Read-only monitoring user
    user monitoring on >monitorPwd ~* +@read +info +dbsize +lastsave +@connection
    ```

After saving the configuration, I restarted the service to apply the changes.

```bash
sudo systemctl restart redis-server
sudo systemctl status redis-server
```


>**[Screenshot 2 : Showing sudo systemctl status redis-server after ACL config]**

![](img/6a-2.png)

---

### Step 2: Testing ACL and RBAC
I verified the permissions for both users.
*   **Admin Test:** I logged in as `admin`. I successfully verified my identity with `ACL WHOAMI` and performed basic `SET`/`GET` operations on a generic key.
    ```bash
    redis-cli -u redis://admin:adminStrongPwd@127.0.0.1:6379
    ```

*   **App User Test:** I logged in as `app_user`. When I tried to run `ACL WHOAMI`, I received a `NOPERM` error, proving that administrative commands were blocked. I successfully wrote to `session:user123`, but when I attempted to write to `otherkey`, Redis returned a `NOPERM` error because it did not match the allowed pattern `~session:*`.
    ```bash
    redis-cli -u redis://app_user:appStrongPwd@127.0.0.1:6379
    ```

>**[Screenshot 3 : Admin testing results]**

![](img/6a-3.png)


> **[Screenshot 4: App_user testing showing OK for session keys and NOPERM for others]**

![](img/6a-4.png)

---

### Step 3: Enabling TLS Encryption
To protect data in transit, I implemented TLS encryption.

#### A. Certificate Generation and Verification
I generated a self-signed Certificate Authority (CA) and a server certificate. I stored these in `/etc/redis/tls/`. To ensure the integrity of my certificates, I compared the MD5 checksums of the certificate modulus and the private key modulus. They matched perfectly, confirming a valid pair.

```bash
mkdir -p /etc/redis/tls
cd /etc/redis/tls

# 1. Create a private key for CA (Certificate Authority)
openssl genrsa -out ca.key 4096

# 2. Create a self-signed CA certificate
openssl req -x509 -new -nodes -key ca.key -sha256 -days 365 \
  -out ca.crt \
  -subj "/C=BT/ST=Chukha/L=Phuntsholing/O=DBS302/OU=Lab/CN=redis-lab-ca"

# 3. Create a private key for the Redis server
openssl genrsa -out redis.key 4096

# 4. Create a certificate signing request (CSR) for Redis server
openssl req -new -key redis.key -out redis.csr \
  -subj "/C=BT/ST=Chukha/L=Phuntsholing/O=DBS302/OU=Lab/CN=localhost"

# 5. Sign the server certificate with the CA
openssl x509 -req -in redis.csr -CA ca.crt -CAkey ca.key -CAcreateserial \
  -out redis.crt -days 365 -sha256

```

>**[Screenshot 5: ls -la of /etc/redis/tls folder]**

![](img/6a-5.png)

>**[Screenshot 6: openssl md5sum verification showing identical hashes]**

![](img/6a-6.png)

#### B. TLS Configuration
I updated the Redis configuration to disable the standard TCP port (`port 0`) and enable the TLS port (`tls-port 6379`). I mapped the paths for the CA certificate, server certificate, and private key.

```bash
tls-port 6379
tls-cert-file /etc/redis/tls/redis.crt
tls-key-file /etc/redis/tls/redis.key
tls-ca-cert-file /etc/redis/tls/ca.crt
tls-auth-clients no
```

> **[Screenshot 9: grep output showing port 0 and tls-port 6379]**

![](img/6a-7.png)

**[Screenshot 10: Successful systemctl restart after TLS config]**

![](img/6a-8.png)

#### C. Secure Connection Verification
I tested the connection using `redis-cli` with the `--tls` and `--cacert` flags. By using the `rediss://` protocol, I confirmed that the connection was only possible through the encrypted tunnel.

> **[Screenshot 12: Successful TLS connection as app_user]**

![](img/6a-9.png)

---

### Step 4: Python Application Integration
Finally, I wrote a Python script (`redis_secure_demo.py`) to simulate a real-world application. The script used an SSL context to load the CA certificate and authenticated using the restricted `app_user` credentials. The script successfully connected and retrieved data over the encrypted link.

```python
import redis

def create_redis_client():
    client = redis.Redis(
        host="127.0.0.1",
        port=6379,
        username="app_user",
        password="appStrongPwd",
        ssl=True,
        ssl_ca_certs="/etc/redis/tls/ca.crt",
        ssl_cert_reqs="none",  # OK for testing, not for production
        decode_responses=True,
    )
    return client

if __name__ == "__main__":
    try:
        r = create_redis_client()

        # Test connection with a simple command
        r.ping()
        print("Connected to Redis successfully")

        # Set and get a value
        r.set("session:python_demo", "hello from python")
        value = r.get("session:python_demo")

        print("Value:", value)

    except Exception as e:
        print("Error:", e)
```

> **[Screenshot 13: Python script execution output]**

![](img/6a-10.png)

---

## 4. Conclusion
Through this practical, I successfully transitioned a Redis instance from an insecure, open state to a hardened production-ready state. By implementing **ACLs**, I ensured that users only have access to the data they need. By implementing **TLS**, I ensured that sensitive data is protected from network sniffing. This multi-layered approach is essential for securing NoSQL databases in modern environments.

---