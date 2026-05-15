# Case Studies in Innovation & Disciplined Entrepreneurship
### CSI – Stripe | CSII – Notion | CSIII – M-Pesa
**Framework: Bill Aulet's 24 Steps to a Successful Startup (MIT Disciplined Entrepreneurship)**

---

## The 24 Steps Framework (Reference)

Bill Aulet's *Disciplined Entrepreneurship* (MIT, 2013) outlines 24 structured steps across six themes:

| # | Step | Theme |
|---|------|--------|
| 1 | Market Segmentation | Who is your customer? |
| 2 | Select a Beachhead Market | Who is your customer? |
| 3 | Build an End User Profile | Who is your customer? |
| 4 | Calculate the TAM Size for Beachhead Market | Who is your customer? |
| 5 | Profile the Persona for the Beachhead Market | Who is your customer? |
| 6 | Full Life Cycle Use Case | What can you do for your customer? |
| 7 | High-Level Product Specification | What can you do for your customer? |
| 8 | Quantify the Value Proposition | What can you do for your customer? |
| 9 | Identify Your Next 10 Customers | What can you do for your customer? |
| 10 | Define Your Core | What can you do for your customer? |
| 11 | Chart Your Competitive Position | How does your customer acquire your product? |
| 12 | Determine the Customer's Decision-Making Unit (DMU) | How does your customer acquire your product? |
| 13 | Map the Process to Acquire a Paying Customer | How does your customer acquire your product? |
| 14 | Calculate TAM Size for Follow-on Markets | How does your customer acquire your product? |
| 15 | Design a Business Model | How do you make money? |
| 16 | Set Your Pricing Framework | How do you make money? |
| 17 | Calculate the Lifetime Value (LTV) of an Acquired Customer | How do you make money? |
| 18 | Map the Sales Process to Acquire a Customer | How do you make money? |
| 19 | Calculate the Cost of Customer Acquisition (COCA) | How do you make money? |
| 20 | Identify Key Assumptions | How do you design and build your product? |
| 21 | Test Key Assumptions | How do you design and build your product? |
| 22 | Define the Minimum Viable Business Product (MVBP) | How do you design and build your product? |
| 23 | Show That "The Dogs Will Eat the Dog Food" | How do you scale your business? |
| 24 | Develop a Product Plan | How do you scale your business? |

---

---

# CSI – Stripe: Online Payment Infrastructure (2010)

---

## a) Background Analysis

### Origins and Founding

Stripe was founded in 2010 by two Irish brothers — **Patrick Collison** (CEO) and **John Collison** (President) — who had emigrated to the United States in 2006. Patrick enrolled at MIT while John attended Harvard. Both had prior entrepreneurial experience: their earlier venture, **Auctomatic**, a tool for eBay sellers, was acquired for $5 million in 2008, demonstrating the brothers' ability to identify and solve pain points for online businesses.

### The Problem They Identified

At the time of Stripe's founding, accepting payments online was an extraordinarily painful process for developers and startups. Integrating with incumbent payment processors such as PayPal or working directly with banks required:

- **Weeks of administrative and compliance paperwork** to open merchant accounts.
- **Complex, poorly documented APIs** that were not built with developers in mind.
- **High fees and restrictive terms**, often locking small businesses out of the ecosystem entirely.

Patrick Collison described the problem bluntly: *"It should be easier to charge for things on the internet."* The brothers recognized a massive market gap between the growing wave of internet businesses and the archaic financial plumbing required to serve them.

### Initial Development

The brothers began building Stripe — originally called **/dev/payments** — while still enrolled in college. They entered **Y Combinator** in 2010, though notably they did not participate in the traditional Demo Day. The name was changed from /dev/payments to "Stripe" because Delaware incorporation rules prohibited leading slashes in company names, and the founders needed a name that could also appeal to traditional banking partners.

### Early Funding and Investors

In 2011, Stripe raised **$2 million** from a prestigious group of investors, including:
- **Peter Thiel** (PayPal co-founder)
- **Elon Musk** (then-PayPal investor)
- **Sequoia Capital**, **Andreessen Horowitz**, and **SV Angel**

This investor pool was strategically important: Thiel and Musk brought deep credibility in payments and fintech, helping Stripe establish legitimacy with banks and financial institutions.

### Core Product and Innovation

Stripe's first product, **Stripe Payments**, launched in 2010 with a radical value proposition: any developer could integrate online payment acceptance into their application with **just seven lines of code**. This was a paradigm shift. Instead of weeks of integration work, a startup could be accepting credit card payments in minutes.

In 2012, Stripe launched **Stripe Connect**, enabling multi-party payment flows for marketplaces and platforms, quickly attracting companies like Lyft, Postmates, and Shopify.

### Business Context

Stripe launched at a time when the internet economy was exploding — the iPhone had been introduced in 2007, cloud services (AWS) were democratizing server infrastructure, and millions of entrepreneurs were starting online businesses. Stripe positioned itself as the payment infrastructure layer for this new economy.

---

## b) The 24 Steps Applied to Stripe (5 Key Steps)

### Step 2 – Select a Beachhead Market

**Which:** Stripe's beachhead market was **early-stage technology startups and individual developers** in Silicon Valley and the broader US tech ecosystem.

**How:** Rather than targeting established enterprises (who had existing payment relationships with banks) or consumers, the Collisons focused obsessively on developers and technical founders. They chose this segment because:
- Developers were the decision-makers for payment integration in startups.
- This group was deeply frustrated by existing solutions.
- A developer-first beachhead would create **bottom-up organic growth**: developers who used Stripe in startup jobs would carry it to new companies they started.
- The segment was small enough to dominate but influential enough to create network effects.

Stripe initially did not take on large enterprise clients, ensuring they could nail product-market fit within the tech startup community before expanding.

---

### Step 5 – Profile the Persona for the Beachhead Market

**Which:** The persona was a **technical co-founder or lead developer at an early-stage internet startup**.

**How:** Stripe built a very precise picture of their ideal customer:
- **Age:** 22–35, likely male, coding-literate.
- **Situation:** Building a SaaS product, marketplace, or e-commerce site; has limited resources and time.
- **Pain:** Has tried to integrate PayPal or traditional merchant accounts and found the documentation terrible and process slow.
- **Goal:** Ship fast, focus on their product — not fight with financial infrastructure.
- **Behaviour:** Reads Hacker News, active on GitHub, attends YC-related events, trusts peer recommendations over advertising.

This persona shaped every product and marketing decision. Stripe's documentation, API design, and developer experience were all optimized for this specific person. The famous Stripe Dashboard and the clarity of Stripe's API documentation became industry benchmarks because they were built with this persona's frustration in mind.

---

### Step 8 – Quantify the Value Proposition

**Which:** Stripe quantified the value it delivered to developers in concrete, measurable terms.

**How:** The value proposition was expressed in two dimensions:

1. **Time savings:** Traditional payment integration took **2–8 weeks** of developer work. Stripe's API reduced this to **hours or even minutes** (the "7 lines of code" promise). For a startup burning runway, this time saving translated directly to **weeks of engineering salary saved** — potentially $10,000–$40,000 in developer cost.

2. **Revenue unlocking:** Many startups simply delayed launching because payments were too complex. Stripe's ease of use **unlocked revenue** that would otherwise not exist. One early customer, the gaming platform DISQUS, credited Stripe with enabling them to monetize in days rather than months.

Stripe also offered transparent, flat-rate pricing (2.9% + $0.30 per transaction) with no hidden fees — a stark contrast to legacy processors with complex fee schedules and setup costs.

---

### Step 15 – Design a Business Model

**Which:** Stripe adopted a **transaction-fee-based business model** — taking a percentage of every payment processed.

**How:** Stripe's model had several elegant properties:

- **Aligned incentives:** Stripe only made money when customers made money. This built trust and created a partnership dynamic.
- **No upfront cost:** Zero setup fees, no monthly minimums, no long-term contracts. This removed all friction to adoption for cash-constrained startups.
- **Scalable revenue:** As Stripe's customers grew, Stripe's revenue grew automatically without any sales effort.
- **The pricing:** **2.9% + $0.30 per successful card charge** — simple, transparent, and competitive.

As Stripe matured, they expanded the business model beyond payments: **Stripe Atlas** (incorporation), **Stripe Issuing** (card issuing), **Stripe Treasury** (banking-as-a-service), and **Stripe Tax** (automated sales tax). Each new product deepened the revenue relationship with existing customers while expanding the addressable market.

---

### Step 22 – Define the Minimum Viable Business Product (MVBP)

**Which:** Stripe's MVBP was the **Stripe Payments API** — a payment processing solution requiring only a few lines of code, with a dashboard, and no merchant account setup required.

**How:** The MVBP satisfied three criteria:
1. **The customer gets real value:** Startups could actually accept credit card payments on day one — not a prototype, but real, live transactions.
2. **You learn from it:** Every integration, every error, every developer support ticket taught Stripe exactly where the product needed improvement.
3. **The customer pays for it:** Stripe took a fee on every transaction processed, making the MVBP a live revenue-generating product from launch.

Stripe deliberately kept the initial product **narrow** — it only handled card payments. They did not try to build invoicing, subscriptions, or banking from the start. This focus allowed them to do one thing exceptionally well before expanding.

---

### Step 24 – Develop a Product Plan

**Which:** Stripe had a clear product roadmap that expanded from the beachhead into adjacent markets over time.

**How:** The product plan followed a deliberate "land and expand" strategy:

- **Phase 1 (2010):** Stripe Payments — core card processing API for startups.
- **Phase 2 (2012):** Stripe Connect — multi-party payments for marketplaces (Lyft, Shopify).
- **Phase 3 (2014–2016):** Stripe Billing, Radar (fraud detection), Atlas (business formation).
- **Phase 4 (2018–2020):** Stripe Treasury (banking), Issuing (card creation), Terminal (in-person payments).
- **Phase 5 (2021–present):** Stripe Tax, revenue recognition, data analytics, and crypto (Bridge acquisition).

Each phase leveraged the trust and customer relationships built in the previous phase, transforming Stripe from a payment processor into a **full-stack financial infrastructure company**.

---

## c) Current Status and Replicability in Bhutan

### Current Status (2025–2026)

As of early 2026, Stripe is one of the most valuable private technology companies in the world:

| Metric | Value |
|--------|-------|
| **Valuation** | $159 billion (February 2026 tender offer) |
| **Annual Revenue** | $5.11 billion (2024, +28% YoY) |
| **Total Payment Volume** | $1.9 trillion (2025) |
| **Transactions/Minute** | 50,000+ |
| **Employees** | ~8,000 |
| **Products** | Payments, Connect, Billing, Tax, Atlas, Treasury, Issuing, Terminal, Radar |

Stripe processed $1.4 trillion in payment volume in 2024, growing to $1.9 trillion in 2025 — a 34% year-over-year increase. The company made its largest acquisition — crypto payments startup **Bridge** for $1.1 billion — in 2024, signaling its move into blockchain-based payment rails.

Stripe remains private but has completed multiple tender offers to provide liquidity to employees and early investors, suggesting a future IPO remains on the horizon.

### Replicability in Bhutan

**Opportunities:**
- Bhutan's Royal Monetary Authority (RMA) has established a **FinTech Regulatory Sandbox** (2024), providing a legal framework for testing new payment innovations.
- The existing **Bhutan Financial Switch** and **Bhutan QR** payment infrastructure provide rails that a Stripe-like layer could sit on top of.
- Bhutan's growing tech-savvy youth population and digital entrepreneurship ecosystem create a potential developer community.
- With Bhutan's ambition to become a digital economy (10% of GDP from digital by 2034), there is political will to support fintech innovation.

**Challenges:**
- Bhutan's **small market size** (~800,000 population) limits the TAM for a payments company; Stripe's model depends on processing high volumes.
- **Cross-border payment complexity** is significant given Bhutan's landlocked geography and Indian Rupee-Ngultrum peg.
- Limited **venture capital ecosystem** and experienced mentors to support scaling.
- Most current digital payment services (BOBL, Tashi, mBoB) are bank-led, not startup-led.

**Verdict:** A scaled replica of Stripe is unlikely in Bhutan due to market size. However, a **developer-friendly payment API layer** built on top of existing RMA infrastructure — aimed initially at local startups and e-commerce platforms — is feasible. Bhutan could benefit from adopting Stripe's *developer experience philosophy* even if the business model must be adapted to the local scale.

---

---

# CSII – Notion: All-in-One Workspace (2013)

---

## a) Background Analysis

### Origins and Founding

Notion was incorporated in **2013** in San Francisco, California, under the name **Notion Labs, Inc.** The company was co-founded primarily by **Ivan Zhao** and **Simon Last**, with additional early team members including Akshay Kothari, Chris Prucha, Jessica Lam, and Toby Schachman.

- **Ivan Zhao** studied Cognitive Science and Fine Arts at the University of British Columbia. His interdisciplinary background — combining computer science with design and human psychology — would later define Notion's product philosophy.
- **Simon Last** brought engineering expertise to complement Zhao's design-driven vision.

### The Core Vision

Zhao and Last were frustrated by the fragmented nature of modern knowledge work. By 2013, teams were using a patchwork of tools:
- **Google Docs** for writing
- **Excel/Google Sheets** for data
- **Trello/Asana** for project management
- **Confluence** for documentation
- **Evernote** for notes

Each tool did one thing, but they did not communicate with each other, creating information silos and productivity friction. Zhao and Last envisioned a single workspace — *"a LEGO of productivity tools"* — where non-technical users could build their own workflows without writing code.

### The 2015 Crisis and Rebuilding

The early version of Notion was built on a sub-optimal technical stack that became unstable. By 2015, after raising approximately **$2 million** from angel investors and hiring four employees, the product was crashing continuously and was becoming unusable.

Faced with the choice of shutting down or starting over, Zhao and Last made a dramatic decision:
- They **laid off all employees**.
- They **left San Francisco** and relocated to **Kyoto, Japan**, where the cost of living was lower and they could work without distraction.
- Zhao spent up to **18 hours a day** redesigning the product from scratch, while Last rebuilt the technical architecture.

This phoenix moment — rebuilding from zero — would become central to Notion's identity and its eventual resilience.

### The Launch of Notion 1.0 and 2.0

- **August 2016:** Notion 1.0 launched — a minimal but functional version of the all-in-one workspace.
- **March 2018:** Notion 2.0 launched, introducing the **block-based editor** — the foundational innovation that differentiated Notion from every competitor. Every piece of content in Notion (a paragraph, a to-do item, a database row, an image) is a "block" that can be moved, transformed, and combined, giving users unprecedented flexibility.

### Growth and the Pandemic Effect

Notion's growth accelerated dramatically during the COVID-19 pandemic (2020), as remote work drove unprecedented demand for collaboration and knowledge management tools. By September 2019 the company reached **1 million users**; by 2021 it had surpassed **20 million**. The company raised a **$275 million Series C** in October 2021 at a **$10 billion valuation**.

---

## b) The 24 Steps Applied to Notion (5 Key Steps)

### Step 2 – Select a Beachhead Market

**Which:** Notion's beachhead market was **individual knowledge workers and small tech-savvy teams**, particularly in the startup and design community.

**How:** Rather than targeting large enterprises with their entrenched tool stacks (Microsoft Office, Salesforce, Confluence), Notion chose to focus on:
- **Individual users** who were frustrated managing personal notes, projects, and writing across multiple apps.
- **Small startup teams** (5–20 people) who had not yet locked into an enterprise software contract.
- **Designers, developers, and content creators** who valued aesthetics and flexibility over raw feature count.

This segment was chosen because they were *opinion leaders*. If a designer or developer loved Notion, they would recommend it to their whole team. If a whole team loved it, they would advocate for it when they moved to larger organizations. Notion's beachhead was small but **virally connected**.

---

### Step 3 – Build an End User Profile

**Which:** The end user profile centered on a **knowledge worker who manages both personal and professional information**.

**How:** Notion profiled their core user as:
- A **25–40-year-old professional** in a creative or technology field.
- **Frustrated** by tool fragmentation — uses 5+ apps daily and loses information constantly.
- **Technically capable** (comfortable with software) but **not a programmer**.
- Values **aesthetic quality** and customizability alongside function.
- Works in environments where **self-directed productivity** matters — freelancers, startup employees, remote workers.
- **Discovery path:** Word of mouth, Twitter, Reddit, or seeing a colleague's Notion workspace.

This profile directly shaped product decisions: the block editor was built to be powerful enough for a developer but intuitive enough for a writer or designer. The aesthetic quality of Notion — typography, whitespace, clean UI — was not cosmetic; it was a direct response to this user's values.

---

### Step 10 – Define Your Core

**Which:** Notion's core competency was the **block-based flexible document system** — a single building block from which any type of content or workflow could be constructed.

**How:** Most productivity tools were built around a fixed structure: Trello has cards and boards, Google Docs has pages, Airtable has spreadsheets. Notion's core innovation was that **everything is a block**, and blocks can be combined in any way:
- A page can contain a database.
- A database row can contain a full document.
- A document can contain a Kanban board.
- Any block can be transformed into any other type of block.

This "atomic" architecture gave Notion a defensible technological and product core that competitors could not easily replicate without rebuilding from scratch. The core also enabled an entire **ecosystem of templates** built by the community, dramatically reducing the time-to-value for new users.

---

### Step 15 – Design a Business Model

**Which:** Notion used a **freemium business model** with usage-gated upgrades.

**How:** The model was structured in layers:

| Plan | Price | Target |
|------|-------|--------|
| **Free** | $0 | Individual users; limited blocks and file uploads |
| **Plus** | $8/month | Individual heavy users and small teams |
| **Business** | $15/member/month | Growing teams; advanced permissions, version history |
| **Enterprise** | Custom | Large organizations; SSO, audit logs, dedicated support |

The freemium tier was deliberately generous enough to be genuinely useful — this was critical to Notion's viral growth. Users would build their personal workspace on the free tier, then *invite colleagues* to collaborate, triggering a conversion to a paid team plan. This "land and expand" motion meant Notion's customer acquisition was largely **product-led** rather than sales-led.

In 2025, AI capabilities were bundled into Business and Enterprise plans, driving upgrades as AI became increasingly central to knowledge work.

---

### Step 21 – Test Key Assumptions

**Which:** Notion systematically tested its core assumptions, most dramatically by **rebuilding the entire product in 2015** when testing revealed the original architecture was flawed.

**How:** Key assumptions tested over Notion's lifecycle:

1. **2013–2015 (Assumption Failure):** Notion assumed they could build a no-code programming tool on their initial technical stack. Testing revealed the stack was unstable and the product crashed under real use. Rather than patch the system, they invalidated the assumption entirely and rebuilt.

2. **2016 (MVBP Test):** The Notion 1.0 launch in 2016 tested whether users would actually pay for and use an all-in-one workspace. Results: slow but steady organic growth confirmed the market existed.

3. **2018 (Block Editor Test):** The Notion 2.0 block editor tested whether users would embrace radical structural flexibility. The viral adoption of 2018–2019 confirmed this was the right bet.

4. **2020 (Team Use Test):** Notion tested whether teams (not just individuals) would adopt the platform for collaboration. The pandemic-era growth from 1M to 4M users confirmed the team collaboration hypothesis.

5. **2025 (AI Assumption):** Notion tested whether AI features would drive tier upgrades. Crossing $500M ARR confirms this assumption held.

---

### Step 22 – Define the Minimum Viable Business Product (MVBP)

**Which:** Notion 1.0 (August 2016) was the MVBP — a simple but real implementation of the block-based workspace concept.

**How:** Notion 1.0 included:
- A basic **block editor** for creating pages and documents.
- Simple **to-do lists and note-taking** functionality.
- Rudimentary **database views** (table and list).
- A free tier and a paid tier, making it a real business product, not a prototype.

Critically, this MVBP delivered real value (users could replace Evernote and Google Docs with it), generated real revenue (paid subscribers from day one), and taught the team exactly which features to build next based on user behavior and support tickets.

The 2015 decision to rebuild was itself a form of MVBP discipline — stripping away complexity to find the irreducible core of what Notion needed to be.

---

## c) Current Status and Replicability in Bhutan

### Current Status (2025–2026)

| Metric | Value |
|--------|-------|
| **Annual Recurring Revenue** | $500M+ (crossed in September 2025) |
| **Total Users** | 100+ million (as of 2024) |
| **Paying Customers** | 4+ million |
| **Valuation** | $10 billion (last round, 2021) |
| **Employees** | ~500 |
| **Key Features (2025)** | Notion AI Agents, MCP connectors, Enterprise Search, AI Meeting Notes |

In September 2025, Notion launched **version 3.0** with autonomous AI Agents capable of pulling data from multiple sources and automating knowledge workflows. The company crossed $500M in annualized revenue, riding the AI productivity wave, while facing increasing competition from Microsoft 365 Copilot and Google Workspace AI. Notion's 90% of business coming from team (multiplayer) usage confirms its evolution from a personal tool to a team platform.

### Replicability in Bhutan

**Opportunities:**
- Bhutan's growing emphasis on **digital governance and e-services** creates demand for knowledge management tools among government departments, NGOs, and universities.
- The **Royal University of Bhutan** and emerging tech education programs could use a Notion-like platform for student and faculty knowledge management.
- Bhutan's **startup ecosystem** (concentrated in Thimphu) has a small but growing community of knowledge workers who are currently using fragmented tools.
- Notion's model of starting small (individual users → teams) aligns with Bhutan's community-centered cultural values.

**Challenges:**
- **Market size:** With ~800,000 people, Bhutan's domestic TAM for a knowledge work SaaS product is very small. Sustainable revenue at local pricing would be difficult.
- **Internet infrastructure:** While mobile internet reaches 95% of the population, reliable broadband for collaborative real-time editing remains uneven outside Thimphu.
- **Competition from free global tools:** Notion itself, Google Workspace, and Microsoft 365 are available to Bhutanese users, making local competition difficult.

**Verdict:** Building a direct Notion competitor in Bhutan is not commercially viable. However, Notion's *philosophy* — block-based, flexible, no-code tools for knowledge work — is highly **relevant as an approach** for building digital governance tools, educational platforms, or community knowledge systems adapted to Bhutanese languages and contexts. The **bootstrapped, intentional design process** Zhao used in Kyoto is a directly applicable model for Bhutanese entrepreneurs working with limited resources.

---

---

# CSIII – M-Pesa: Mobile Money Transfer (2007)

---

## a) Background Analysis

### Origins and Context

**M-Pesa** (M for *Mobile*, Pesa from Swahili for *money*) was launched in **March 2007** by **Safaricom**, Kenya's largest mobile network operator, with **Vodafone** as a minority shareholder (40%). The service was built to address one of the most severe financial exclusion challenges in Sub-Saharan Africa.

### The Problem M-Pesa Solved

Before M-Pesa, Kenya's financial landscape was stark:
- By 2006, **41 commercial banks** had established only **400 branches and 600 ATMs** to serve **36 million Kenyans**.
- Only **18.9% of Kenyans** had a bank account.
- The majority of Kenyans — particularly **rural populations and the urban poor** — relied entirely on **cash or informal money transfer** methods (sending cash via bus drivers, hawala networks, or physically traveling with money).
- These informal methods were **slow, insecure, and expensive**, with loss due to theft or corruption commonplace.

### Conceptual Origins

The concept of M-Pesa did not emerge from a corporate boardroom alone. Researchers at the **UK Department for International Development (DFID)** observed that Kenyans were already informally transferring **prepaid mobile airtime** as a proxy for money — a workaround that demonstrated clear demand for a mobile-based financial transfer service.

Vodafone partnered with Safaricom and convened workshops with financial institutions and microfinance organizations to test the feasibility. A **pilot program** was conducted in 2005 in partnership with Faulu Kenya, a microfinance institution, to test whether microfinance loan repayments could be handled via mobile phone.

### Technical Architecture

M-Pesa's genius was its **simplicity**. Rather than requiring a smartphone or internet connection, the service was built on **basic SMS technology** — accessible to anyone with a feature phone, which by 2007 was increasingly common across Kenya. The flow was:

1. A user deposits cash at an **M-Pesa agent** (shopkeeper, pharmacist, kiosk operator) in exchange for **e-float** stored on their SIM card.
2. The user sends money via **PIN-secured SMS** to any other mobile number.
3. The recipient redeems the e-float for **cash** at any M-Pesa agent.

The agent network was critical: by 2018, M-Pesa had **110,000 agents across Kenya** — far exceeding the number of bank branches and ATMs combined.

### Regulatory Environment

Safaricom launched M-Pesa under a unique regulatory arrangement: the Central Bank of Kenya granted a **special waiver** allowing Safaricom — a telecom company, not a bank — to hold customer funds in a trust account managed by Commercial Bank of Africa. This regulatory flexibility was essential; in countries where regulators required mobile money to be operated only by licensed banks, M-Pesa's model failed (as seen in South Africa).

### Societal Impact

Research published in the **American Economic Review** (Suri & Jack, 2016) found that M-Pesa lifted **194,000 Kenyan households out of poverty** — approximately 2% of Kenyan households — by enabling women in particular to shift from agricultural work to business and retail. M-Pesa fundamentally changed the economic fabric of Kenya.

---

## b) The 24 Steps Applied to M-Pesa (5 Key Steps)

### Step 2 – Select a Beachhead Market

**Which:** M-Pesa's beachhead market was **urban-to-rural remittance senders** — specifically, urban workers in Nairobi who regularly sent money back to rural family members.

**How:** Safaricom identified a very specific, high-frequency use case: the **"domestic remittance corridor."** Millions of Kenyans had moved from rural areas to Nairobi for work, but their families remained in the countryside. They needed to send money home regularly — weekly or monthly — but had no safe, reliable, or affordable way to do so.

This beachhead was chosen because:
- The **pain was acute and universal** — everyone in this demographic had this problem.
- The **frequency was high** — weekly or monthly transactions generate recurring revenue.
- The **network effect was instant** — if a sender in Nairobi registered, they would immediately recruit their rural recipient to register in order to receive money.
- The market was **large enough** to generate sustainable volume but **focused enough** to be won decisively.

Safaricom did not try to be a bank from the beginning. They focused on this one corridor, executed it perfectly, and expanded from there.

---

### Step 3 – Build an End User Profile

**Which:** M-Pesa profiled two interlocking end users: the **sender** and the **recipient**.

**How:**

**Sender Profile:**
- Male, aged 20–35.
- Lives in Nairobi; works in construction, domestic service, or the informal economy.
- Earns between **KES 5,000–15,000/month** (~$50–$150).
- Currently sends money home via **bus drivers, friends, or hawala agents** — unreliable, takes days, often involves loss.
- Owns a **basic mobile phone** (Nokia feature phone).
- **Decision trigger:** Safety, reliability, and speed of getting money to family.

**Recipient Profile:**
- Female, aged 30–55, living in a rural area.
- Relies on remittances for household expenses, school fees, food.
- Has **limited mobility** to travel to a town for banking.
- Also owns or has access to a **basic mobile phone**.
- **Decision trigger:** Receiving money faster and without the anxiety of cash in transit.

This dual-profile design was critical: M-Pesa designed the agent network, the SMS interface, and the fee structure to serve both personas simultaneously. The product had to be simple enough for a rural grandmother and reliable enough for a construction worker to trust with his month's salary.

---

### Step 8 – Quantify the Value Proposition

**Which:** M-Pesa quantified the value it delivered against the existing alternatives — informal cash transfer methods.

**How:** Before M-Pesa, sending KES 2,000 (~$20) from Nairobi to a rural town involved:
- Handing cash to a **bus driver** — who might lose it, steal it, or deliver it 2–3 days late.
- Or traveling personally — costing **2× bus fare** plus a full day of lost work income.
- **Risk of theft** in transit: informal couriers had no accountability.
- **Total cost (informal):** KES 200–400 in courier fees + risk premium (loss/delay) — effectively 10–20% of the amount sent.

M-Pesa's value proposition:
- **Cost:** KES 30–50 to send KES 2,000 — a **transaction fee of ~1.5–2.5%**, far cheaper than informal alternatives.
- **Speed:** Money arrives in **seconds** via SMS — not days.
- **Security:** PIN-protected, with Safaricom's network infrastructure guaranteeing delivery.
- **Convenience:** No travel required; nearest agent is often within walking distance.

The quantified value — faster, cheaper, safer, more convenient — was overwhelming. For M-Pesa's core customer, this was not a marginal improvement but a **transformative one**.

---

### Step 11 – Chart Your Competitive Position

**Which:** M-Pesa mapped the competitive landscape and identified a position of **near-total strategic differentiation** at launch.

**How:** In 2007, M-Pesa had no direct competitor in mobile money in Kenya:

| Provider | Speed | Cost | Accessibility | Safety |
|----------|-------|------|---------------|--------|
| **Commercial Banks** | Days | High (wire fees) | Very low (400 branches) | High |
| **Bus Couriers (informal)** | 1–3 days | 10–20% of amount | High (but physical) | Very low |
| **Personal travel** | Hours | 2× bus fare + lost wages | N/A | Moderate |
| **M-Pesa** | Seconds | 1.5–2.5% | Very high (agent network) | High |

M-Pesa occupied a unique position: the **only provider that was simultaneously low-cost, fast, safe, and accessible** to unbanked populations. This position was defended by Safaricom's existing telecom infrastructure (which new entrants could not quickly replicate), its brand trust among Kenyan consumers, and the **regulatory waiver** that competitors would not easily obtain.

This competitive map made M-Pesa's launch strategy straightforward: there was no incumbent to displace in mobile money. The competition was *informal systems*, not formal businesses.

---

### Step 15 – Design a Business Model

**Which:** M-Pesa used a **transaction-fee-based business model**, generating revenue from small fees on every money transfer.

**How:** The business model was built on several revenue streams:

1. **Transfer fees:** A sliding scale fee based on the amount sent, ranging from approximately KES 11 for small amounts to KES 110 for larger transfers (up to KES 70,000). These were small individually but massive in aggregate given Kenya's population.

2. **Agent commission:** Agents earned a small commission on each transaction they facilitated. Safaricom paid agents for deposits and withdrawals, creating a **self-sustaining distributed retail network** without owning physical infrastructure.

3. **Float income:** Safaricom held the aggregate of all M-Pesa customer balances in a **trust account** at Commercial Bank of Africa, earning interest on this pooled float — a significant revenue source at scale.

4. **Expansion services:** As the platform matured, M-Pesa added **M-Shwari** (savings and loans), **M-Tiba** (health savings), **Lipa Na M-Pesa** (merchant payments), and international remittances — each adding new revenue layers on top of the base transfer business.

The model was self-financing: low transaction fees at high volume generated substantial revenue, while the agent network operated on commission rather than salary, keeping fixed costs low.

---

### Step 22 – Define the Minimum Viable Business Product (MVBP)

**Which:** M-Pesa's MVBP was the **basic SMS-based peer-to-peer money transfer service**, tested through the 2005 pilot program before full launch in 2007.

**How:** The pilot ran with Faulu Kenya's microfinance clients:
- Users received microfinance loans disbursed via M-Pesa.
- Users repaid loans via M-Pesa.
- Agents were simple shopkeepers who received training to handle cash-in/cash-out.

The pilot validated three critical assumptions:
1. **Users would trust a mobile phone to hold their money** — critical given Kenya's history of bank failures.
2. **Agents could be trained and would maintain adequate float** — the distributed agent model would work.
3. **SMS-based transactions were reliable enough** for financial use on Safaricom's network.

When all three assumptions were confirmed, Safaricom launched M-Pesa to the full Kenyan market in March 2007. Within one year, **1.6 million Kenyans** had registered. The MVBP — simple, SMS-based, agent-facilitated transfer — was sufficient to demonstrate extraordinary product-market fit.

---

## c) Current Status and Replicability in Bhutan

### Current Status (2025–2026)

| Metric | Value |
|--------|-------|
| **Monthly Active Users** | 70+ million across 8 countries |
| **Countries of Operation** | Kenya, Tanzania, Mozambique, DRC, Lesotho, Ghana, Egypt, Ethiopia |
| **Agent Network (Kenya)** | 160,000+ agents |
| **Transaction Value (Kenya)** | ~56% of Kenya's GDP flows through M-Pesa annually |
| **Revenue Contribution** | ~40% of Safaricom's total revenue |
| **New Features (2025)** | Investment products, blockchain cross-border settlement (MOU with ADI Foundation) |

In September 2025, M-Pesa underwent a major platform upgrade to handle increased transaction volumes, reduce outages, and enable faster feature deployment across all eight markets. In December 2025, M-Pesa Africa signed an MOU with the ADI Foundation to pilot **blockchain-based cross-border payment settlement** — a significant technological evolution from its original SMS architecture.

M-Pesa's expansion to South Africa, India, Romania, and Albania failed due to higher banking penetration rates, regulatory barriers, and domestic competition — illustrating that the model's success is context-dependent, not universally transferable.

### Replicability in Bhutan

**Opportunities:**
- Bhutan shares several of M-Pesa's original market conditions: a **significant unbanked or underbanked rural population**, geographic isolation of villages, and a strong **mobile phone penetration** (95% mobile internet coverage).
- The **Bank of Bhutan mobile banking app** (launched 2015) and four existing **e-wallet providers** show that the infrastructure and regulatory groundwork already exist.
- Bhutan's **RMA FinTech Regulatory Sandbox** mirrors the regulatory flexibility that made M-Pesa possible in Kenya — the RMA has demonstrated willingness to allow non-bank entities to innovate in financial services.
- **Bhutan QR** and the **Bhutan Financial Switch** provide interoperability infrastructure that M-Pesa had to build from scratch.
- Bhutan's **rural-urban income disparity** and seasonal worker migration (e.g., farmers, construction workers) create a domestic remittance corridor similar to Kenya's.

**Challenges:**
- **Small market:** Bhutan's population (~800,000) means transaction volumes will be much lower, making the per-transaction fee model less financially attractive for a private operator.
- **Existing banking infrastructure:** Bhutan's banking penetration is higher than Kenya's was in 2007, meaning M-Pesa's "only alternative to informal systems" positioning is weaker.
- **Ngultrum-Rupee peg:** Bhutan's currency is pegged 1:1 to the Indian Rupee, creating a natural cross-border payment use case with India — but also regulatory complexity for cross-border mobile money.
- **Competition from Indian UPI:** India's Unified Payments Interface (UPI) is increasingly being adopted for cross-border use, and many Bhutanese already use Indian payment apps informally.

**Verdict:** The M-Pesa model is the **most directly replicable** of the three case studies for Bhutan. A **Bhutan-specific mobile money service** targeting rural-to-urban remittances and agricultural payment collection — built on the existing RMA infrastructure with a simplified agent model — is commercially viable. The key lesson from M-Pesa is the importance of **regulatory partnership** (as Safaricom had with the Central Bank of Kenya) and the **agent network as the physical last mile**. Bhutan's existing network of community cooperatives, post offices, and rural banking agents could serve this function.

---

---

# Comparative Summary Table

| Dimension | Stripe (CSI) | Notion (CSII) | M-Pesa (CSIII) |
|-----------|-------------|---------------|-----------------|
| **Founded** | 2010, San Francisco | 2013, San Francisco | 2007, Nairobi, Kenya |
| **Founders** | Patrick & John Collison | Ivan Zhao & Simon Last | Safaricom / Vodafone |
| **Core Problem** | Online payment complexity for developers | Fragmented productivity tools | Financial exclusion of unbanked populations |
| **Beachhead Market** | Tech startup developers | Individual knowledge workers | Urban-to-rural remittance senders |
| **Key Innovation** | 7-line code payment API | Block-based flexible workspace | SMS-based mobile money via agent network |
| **Business Model** | Transaction fee (2.9% + $0.30) | Freemium SaaS ($0–$15+/month) | Per-transfer fee + float income |
| **MVBP** | Stripe Payments API (2010) | Notion 1.0 (2016) | SMS transfer pilot with Faulu Kenya (2005) |
| **Current Scale** | $159B valuation, $1.9T TPV | $500M ARR, 100M users | 70M+ users, 8 countries |
| **Bhutan Replicability** | Low (market too small) | Low (dominated by global tools) | **High** (rural remittance corridor exists) |

---

# References

1. **Stripe Wikipedia** — [https://en.wikipedia.org/wiki/Stripe,_Inc.](https://en.wikipedia.org/wiki/Stripe,_Inc.)

2. **Stripe Founding Story — Contrary Research** — [https://research.contrary.com/company/stripe](https://research.contrary.com/company/stripe)

3. **Stripe 2025 Annual Letter** — [https://stripe.com/newsroom/news/stripe-2025-update](https://stripe.com/newsroom/news/stripe-2025-update)

4. **Stripe Reaches $159B Valuation — PYMNTS** — [https://www.pymnts.com/news/fintech-investments/2026/stripe-reaches-record-valuation-global-volume-hits-2-trillion-dollars/](https://www.pymnts.com/news/fintech-investments/2026/stripe-reaches-record-valuation-global-volume-hits-2-trillion-dollars/)

5. **Stripe Founders Story — KITRUM** — [https://kitrum.com/blog/stripe-founders-the-story-of-collison-brothers/](https://kitrum.com/blog/stripe-founders-the-story-of-collison-brothers/)

6. **How Stripe Grows — HowTheyGrow** — [https://www.howtheygrow.co/p/how-stripe-grows](https://www.howtheygrow.co/p/how-stripe-grows)

7. **Notion Wikipedia** — [https://en.wikipedia.org/wiki/Notion_(productivity_software)](https://en.wikipedia.org/wiki/Notion_(productivity_software))

8. **History of Notion — Bullet.so** — [https://bullet.so/blog/history-of-notion-everything-from-users-funding-and-more/](https://bullet.so/blog/history-of-notion-everything-from-users-funding-and-more/)

9. **Notion Founding Story — Contrary Research** — [https://research.contrary.com/company/notion](https://research.contrary.com/company/notion)

10. **Notion Near Failure to $10B Unicorn** — [https://whatastartup.substack.com/p/how-notion-went-from-near-failure-to-a-10-billion-dollars-unicorn](https://whatastartup.substack.com/p/how-notion-went-from-near-failure-to-a-10-billion-dollars-unicorn)

11. **Notion $500M Revenue — CNBC** — [https://www.cnbc.com/2025/09/18/notion-launches-ai-agent-as-it-crosses-500-million-in-annual-revenue.html](https://www.cnbc.com/2025/09/18/notion-launches-ai-agent-as-it-crosses-500-million-in-annual-revenue.html)

12. **Why We Built Notion — Notion About** — [https://www.notion.com/about](https://www.notion.com/about)

13. **M-Pesa Wikipedia** — [https://en.wikipedia.org/wiki/M-Pesa](https://en.wikipedia.org/wiki/M-Pesa)

14. **The M-PESA Wonder: How It All Began — Safaricom Newsroom** — [https://newsroom.safaricom.co.ke/innovation/the-m-pesa-wonder-how-it-all-begun/](https://newsroom.safaricom.co.ke/innovation/the-m-pesa-wonder-how-it-all-begun/)

15. **M-PESA: Transforming Kenya's Economy — Safaricom** — [https://newsroom.safaricom.co.ke/innovation/mobile-money-africas-force-for-social-good/](https://newsroom.safaricom.co.ke/innovation/mobile-money-africas-force-for-social-good/)

16. **M-Pesa Business Model — Strategyzer** — [https://www.strategyzer.com/library/m-pesa-business-model](https://www.strategyzer.com/library/m-pesa-business-model)

17. **Mobile Money: The Economics of M-PESA — NBER Working Paper (Jack & Suri)** — [https://www.nber.org/system/files/working_papers/w16721/w16721.pdf](https://www.nber.org/system/files/working_papers/w16721/w16721.pdf)

18. **M-Pesa — Centre for Public Impact** — [https://centreforpublicimpact.org/public-impact-fundamentals/mobile-currency-in-kenya-the-m-pesa/](https://centreforpublicimpact.org/public-impact-fundamentals/mobile-currency-in-kenya-the-m-pesa/)

19. **M-Pesa 18 Years of Innovation — Safaricom** — [https://www.safaricom.co.ke/media-center-landing/press-releases/m-pesa-celebrates-18-years-of-financial-innovation-officially-unveils-investment-product](https://www.safaricom.co.ke/media-center-landing/press-releases/m-pesa-celebrates-18-years-of-financial-innovation-officially-unveils-investment-product)

20. **Bill Aulet — Disciplined Entrepreneurship Framework (MIT)** — [https://www.d-eship.com/about/framework/](https://www.d-eship.com/about/framework/)

21. **Disciplined Entrepreneurship — MIT Sloan Executive Education** — [https://executive.mit.edu/course/disciplined-entrepreneurship/a056g00000URaagAAD.html](https://executive.mit.edu/course/disciplined-entrepreneurship/a056g00000URaagAAD.html)

22. **Bhutan FinTech Regulatory Sandbox 2024 — RMA** — [https://www.rma.org.bt/media/Laws_By_Laws/FinTech%20Regulatory%20Sandbox%20Implementation%20Strategy%202024.pdf](https://www.rma.org.bt/media/Laws_By_Laws/FinTech%20Regulatory%20Sandbox%20Implementation%20Strategy%202024.pdf)

23. **Fintech and Wider Digital Overview of Bhutan 2026 — The Fintech Times** — [https://thefintechtimes.com/fintech-and-wider-digital-overview-of-the-kingdom-of-bhutan-2026/](https://thefintechtimes.com/fintech-and-wider-digital-overview-of-the-kingdom-of-bhutan-2026/)

24. **Bhutan Digital Economy Strategy — UNDP** — [https://www.undp.org/bhutan/publications/kingdom-bhutan-digital-development-and-transformation-strategy](https://www.undp.org/bhutan/publications/kingdom-bhutan-digital-development-and-transformation-strategy)

25. **Bhutan Moves Towards Cashless Society — Daily Bhutan** — [https://www.dailybhutan.com/article/bhutan-moves-towards-becoming-a-cashless-and-digital-society](https://www.dailybhutan.com/article/bhutan-moves-towards-becoming-a-cashless-and-digital-society)

26. **Startup Bhutan: Bootstrap-First Philosophy — Sramana Mitra** — [https://www.sramanamitra.com/2025/10/23/startup-bhutan-why-the-bootstrap-first-philosophy-is-necessary-for-acceleration/](https://www.sramanamitra.com/2025/10/23/startup-bhutan-why-the-bootstrap-first-philosophy-is-necessary-for-acceleration/)

---

*Document prepared as part of IDE (Innovation and Disciplined Entrepreneurship) coursework | SEM 6 | May 2026*