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
Because Open Banking is not ready, users must manually upload and OCR-scan their debt contracts. While this high initial friction creates a "sunk cost" that increases switching costs once completed, the overall workflow depth is low. It functions primarily as an advisory dashboard rather than a deeply integrated utility.

**Named attacker (from partner challenge):**

---

### Data Advantage — _2_/5
*Proprietary signal that compounds with usage. What do you see that OpenAI doesn't?*

**Score rationale:**
ClearNee relies on user-submitted OCR documents and scraped public interest rates. OpenAI or any generic LLM wrapper can process these exact same documents and public data. Without direct bank feeds, ClearNee lacks a compounding, proprietary data advantage in its early stages.

**Named attacker (from partner challenge):**

---

### Platform Exposure — _3_/5
*Encroachment risk × pivot speed. If Apple/Google/OpenAI ships your hero feature native — then what?*

**Score rationale:**
Big Tech (Apple/Google) is unlikely to launch localized Thai debt-refinancing tools natively. However, the risk is high from local platforms: if major Thai commercial banks (who already own the user's financial data) launch native AI debt-advisors, ClearNee’s core feature could be instantly eclipsed.


**Named attacker (from partner challenge):**

---

## Top Vulnerability
<!-- One line: what's the single biggest strategic risk? -->
Relying entirely on manual user uploads (due to lack of Open Banking) creates massive onboarding friction while offering zero proprietary data advantage against traditional banks that decide to build AI features.

## Confidence Level
<!-- H / M / L — how confident are you in this bet after the diagnostic? -->
M (Medium)
