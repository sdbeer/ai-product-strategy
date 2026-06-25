# Three-Axis Vulnerability Diagnostic

## Product
<!-- Name the product you're diagnosing. Real product at your company — not a hypothetical. -->


**Product: ClearNee — AI Personal Debt Manager**
**Your Role: AI Product Manager**

---

## Scores

### Contextual Moat — _3_/5
*Workflow depth × switching cost. Would users leave in a weekend if a competitor showed up?*

**Score rationale:**
Because open banking is unavailable, users must manually upload contracts via OCR. This high initial friction actually creates an accidental switching cost—once a user invests the time to scan all their debt documents, they are unlikely to repeat that tedious setup process on a competitor's app.

**Named attacker (from partner challenge):**

---

### Data Advantage — _2_/5
*Proprietary signal that compounds with usage. What do you see that OpenAI doesn't?*

**Score rationale:**
While we collect proprietary user debt data via OCR , the AI logic relies heavily on publicly available data scraped from websites (interest rates, government programs). OpenAI or any competitor can easily access these public data sources. Our data flywheel only triggers if user-submitted data significantly optimizes repayment algorithms over time.

**Named attacker (from partner challenge):**

---

### Platform Exposure — _3_/5
*Encroachment risk × pivot speed. If Apple/Google/OpenAI ships your hero feature native — then what?*

**Score rationale:**
An LLM like ChatGPT can already analyze a debt contract PDF and output a basic repayment strategy if prompted. However, the foundational models lack localized transaction capabilities (ThaiQR, direct debit)  and deep local regulatory context, giving ClearNee a protective layer of hyper-local execution.


**Named attacker (from partner challenge):**

---

## Top Vulnerability
<!-- One line: what's the single biggest strategic risk? -->
The manual OCR-onboarding friction creates a massive growth bottleneck, while the core AI advisory logic is highly vulnerable to being replicated by commoditized foundational LLMs

## Confidence Level
<!-- H / M / L — how confident are you in this bet after the diagnostic? -->
M (Medium)
