# Data Flywheel Map

> Score each loop 1-5. Your weakest loop is where competitors attack first.
> The four loops below are the M2 starting point - adapt if your product has 2 or 6 loops instead of 4.

## Flywheel Loops

| Loop | What It Measures | Score 1 | Score 5 | Score |
|------|------------------|---------|---------|-------|
| **Correction** | Do users fix AI outputs? Is that signal captured and reused? | No capture | Automated retraining | _2_/5 |
| **Preference** | Does the product learn individual / team preferences over time? | Stateless | Deep personalization | _3_/5 |
| **Domain Context** | Does usage in one area improve quality in adjacent areas? | Siloed | Cross-domain transfer | _2_/5 |
| **Network** | Does each new user / team make the product better for everyone? | Isolated | Strong network effects | _2_/5 |

### Correction Loop - _2_/5
**What you capture today:**
ClearNee captures explicit user corrections when the OCR engine misreads interest rates, loan terms, or due dates from uploaded contracts. It also logs implicit corrections, such as when a user rejects a generated repayment schedule or manually edits an auto-generated refinance application.

**How it compounds:**
Currently, corrections only fix the individual user's profile rather than automatically retraining the underlying model. It compounds weakly because while localized OCR adjustments improve individual dashboard accuracy , the core AI strategic logic remains reliant on static prompts and external web-scraped regulatory data.

### Preference Loop - _3_/5
**What you capture today:**
ClearNee captures a user's chosen debt prioritization philosophy (e.g., favoring the psychological wins of the Snowball method vs. the mathematical optimization of the Avalanche method). It also logs their monthly discretionary income limits, risk tolerance for refinancing, and preferred notification frequencies.

**How it compounds:**
While the app doesn't immediately rewire its core algorithms, it successfully moves beyond a "generic app" by tailoring repayment cadences and tone to individual stress levels. It compounds moderately because as user segments engage, the system learns which behavioral nudges effectively prevent defaults for specific persona archetypes.

### Domain Context Loop - _2_/5
**What you capture today:**
ClearNee captures an aggregate, cross-institutional snapshot of Thai household debt profiles, including localized interest rate premiums, real-world approval criteria for regional refinancing options, and historical user success rates across specific government debt relief programs.

**How it compounds:**
While ClearNee compiles specialized financial profiles, it compounds weakly because the core domain knowledge—such as changing bank interest rates or national regulatory frameworks—is scraped from public websites. Competitors can easily access this public data , meaning usage in one domain doesn't yet create a defensible, proprietary knowledge corpus.

### Network Loop - _2_/5
**What you capture today:**
ClearNee captures aggregated, anonymized success paths across its user base, specifically tracking which micro-segment demographics successfully negotiate debt restructurings, which Thai banking partners approve refinance applications, and the exact friction points causing collective payment defaults.

**How it compounds:**
ClearNee operates in largely isolated user silos where an individual's debt management plan does not directly improve the experience for another user. It compounds weakly because the network effect is passive; data only aggregates into an analytical pool rather than dynamically sharpening the cooperative AI recommendation engine.

**Total Flywheel Score: _9_/20**
**Weakest Loop:**
Corrections Loop, Domain Context Loop, Network Loop

**Fix for weakest loop:**

Corrections Loop Fix: Implement an automated pipeline that anonymizes user OCR corrections and feeds them into a nightly fine-tuning loop, making ClearNee’s proprietary text-extraction engine progressively flawless at reading diverse Thai banking formats.

Domain Context Loop Fix: Partner directly with local debt relief NGOs and financial clinics to integrate non-public case studies, creating a proprietary corpus of historical restructuring approvals that no generic LLM can access.

Network Loop Fix: Aggregating anonymized data from thousands of users with identical creditors allows the AI to calculate collective bargaining leverage, offering banks bulk-restructuring options that lower interest rates for everyone involved.

---

## Encroachment Threat Assessment

### 1. Platform Encroachment
**Attacker:**
Big Tech Foundation Models (e.g., OpenAI, Google).
**Vector:**
Native multimodal document processing. Consumers can already upload a PDF or photo of a debt contract directly into ChatGPT or Gemini and prompt it to "create a monthly debt snowball schedule based on current Thai regulations."  As context windows expand and native OCR perfectly parses local languages, ClearNee's basic text extraction and calculation layer become fully commoditized.
**Time-to-threat:**
Immediate (0–3 months).
**% of value at risk:**
40%.
While Big Tech instantly wipes out ClearNee's core AI advisory logic, they completely lack localized execution layers like ThaiQR, direct integrations with local banks, and direct debit automations, leaving ClearNee last-mile workflow intact.

### 2. Vertical Competitor
**Attacker:**
Niche FinTech Startups / Local Refinance Brokers (e.g., a startup focused exclusively on Thai Mortgage Refinancing or Auto Loan Restructuring).
**Vector:**
Going deep into a single asset class instead of general multi-creditor debt management. This competitor partners deeply with 2–3 major Thai retail banks to get direct API approvals for refinancing applications, bypassing the messy public web scraping that ClearNee relies on.
**Time-to-threat:**
6–12 months.
**% of value at risk:**
30%.
They will cleanly peel away ClearNee's highest-value user segments (home and car owners looking to lower massive monthly interest payments) because their conversion rates and direct bank integrations will yield better approval results than a generic advisor.

### 3. Adjacent Expansion
**Attacker:**
Major Thai Retail Banks / Digital Wallets (e.g., KPlus, SCB Easy, or TrueMoney Wallet).
**Vector:**
Dropping an "External Debt Optimizer" feature into their existing applications as "one more thing." They already possess a massive distribution advantage (millions of daily active Thai users), high user trust, and direct transaction data. They can easily introduce a feature that allows users to snap photos of competitor bank statements to offer an in-app consolidation loan.
**Time-to-threat:**
12–18 months (due to traditional banking legacy cycles and regulatory compliance hurdles).
**% of value at risk:**
If an incumbent bank or massive e-wallet builds this, ClearNee's entire value proposition is nearly erased. They solve the onboarding bottleneck instantly because they already hold the user's main wallet, financial data, and payment execution channels.

---

## 90-Day Encroachment Plan

*Your partner played the Big Tech attacker. What was their plan to kill you?*

**Attacker:**
**Attack vector (target the weakest loop):**
**Weeks 1-4 - what they ship:**
**Weeks 5-8 - how they poach users:**
**Weeks 9-12 - why users don't come back:**
**Your defense:**
