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
**Vector:**
**Time-to-threat:**
**% of value at risk:**

### 2. Vertical Competitor
**Attacker:**
**Vector:**
**Time-to-threat:**
**% of value at risk:**

### 3. Adjacent Expansion
**Attacker:**
**Vector:**
**Time-to-threat:**
**% of value at risk:**

---

## 90-Day Encroachment Plan

*Your partner played the Big Tech attacker. What was their plan to kill you?*

**Attacker:**
**Attack vector (target the weakest loop):**
**Weeks 1-4 - what they ship:**
**Weeks 5-8 - how they poach users:**
**Weeks 9-12 - why users don't come back:**
**Your defense:**
