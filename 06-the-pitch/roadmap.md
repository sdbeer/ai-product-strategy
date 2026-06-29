# Three-Horizon Roadmap & Board Pitch

## Roadmap

### Horizon 1 — Now (0-3 months)
*Quick wins. Ship with existing capabilities.*

| Initiative | Strategy Component | Why it ships now | Confidence |
| --- | --- | --- | --- |
| **5. Integrate Third-Party OCR API** | **Bet** | Core operational necessity to test the initial value proposition and ingestion pipeline. | H |
| **7. Implement Basic OpenAI API Integration** | **Bet** | Baseline MVP requirement to generate debt roadmaps and validate basic core advisory logic. | H |
| **10. Deploy Localized ThaiQR Payment rails** | **Margin** *(User-Mapped)* | Critical for direct monetization and immediate gross margin tracking upon sign-up. | H |
| **1. Data Ingestion Layer (OCR)** | **Bet** | Foundational epic required to unblock the core product onboarding experience. | H |



### Horizon 2 — Next (3-9 months)
*Bets. Requires new capabilities or integrations.*

| Initiative | Strategy Component | Hypothesis | Kill Criteria | Confidence |
| --- | --- | --- | --- | --- |
| **3. Confidence UX & Control Surfaces** | **Contract** | Contextual evidence panels and native manual overrides will keep onboarding drop-off below 80%. | If user onboarding drop-off during manual entry remains above 80% by week 4, we stop. | M |
| **6. Build Split-Screen Interactive Override Panel** | **Contract** | Visual highlighting of errors speeds up corrections and drives the Moat's data feedback loop. | If manual correction time per contract exceeds 5 minutes by week 4, we stop. | M |
| **8. Architect Model Cascading Router** | **Margin** | Routing 70%+ of simple traffic to Gemini Flash protects margins without reducing advice accuracy. | If model cascading routing accuracy drops below 95% within the first month, we stop. | M |
| **9. Design 'Capped Hybrid' Plan Gate** | **Margin** | Paywalling excess scans at $1.50 protects unit economics from outlier power users. | If paid scan add-on attach rate is under 5% by week 6, we stop and restructure pricing. | M |
| **12. Create Emergency Human Validation Queue** | **Guardrails** | A localized Bangkok human audit desk keeps early systemic reliability at the targeted 95%. | If human desk operational costs exceed $5/user within 6 weeks, we stop and automate. | M |
| **2. Advisory Engine & Cost Curve Optimization** | **Margin** | Deep logic tuning combined with routing logic yields the targeted +42.3% net margin shift. | If unit COGS reduction tracks below a 30% margin improvement by week 8, we stop. | M |

### Horizon 3 — Bet (9-18 months)
*Moonshots. High uncertainty, high potential.*

| Initiative | Strategy Component | What must be true first | Confidence |
| --- | --- | --- | --- |
| **4. Governance & Operational Infrastructure** | **Guardrails** | Scale must hit a point where manual code updates cannot keep up with LLM drift. | M |
| **11. Setup 300-Row Golden Dataset Evaluation Matrix** | **Guardrails** | Prompt variations and data extraction volume must be high enough to justify automated test suite maintenance. | M |
| **13. Configure Automated Prompt Version Rollback** | **Guardrails** | The Golden Dataset evaluation must be production-tested and reliably deterministic first. | L |
| **14. Build Automated Web Scraper for Thai Bank Rates** | **Guardrails** | Core onboarding and advisory loops must be stable before introducing dynamic, real-time macro variables. | L |


## Board Pitch

**Thesis (1 sentence):**
ClearNee captures the surging Thai debt advisory market by using an automated document-processing workflow to bypass the country's lack of Open Banking, turning fragmented loan contracts into optimized repayment roadmaps.

**The case:**
1. Why now: Thai household NPLs are skyrocketing in Q3 2026, creating urgent consumer demand, while the complete absence of Open Banking infrastructure means an AI-native OCR workflow is the only viable way to aggregate loan data at scale.
2. What's defensible: Our moat is a proprietary Corrections Loop that automatically feeds anonymized user OCR line-item overrides into a nightly fine-tuning cycle, making our localized Thai contract text-extraction engine progressively harder for generic foundational models to replicate.
3. The economics: Net margin shifts by +42.3%, jumping profit from $8.50 to $19.50 per user/month, achieved by a 90/10 model cascade that routes simple traffic to Gemini Flash and a $1.50 paywall gate to cap outlier power users.

**The risks:**
1. Trust / failure modes: Misreading a complex Thai legal contract interest rate could subject distressed users to incorrect financial liabilities; we mitigate this by enforcing a mandatory human-in-the-loop validation trigger for any document ingestion confidence score below 92%.
2. Scale / governance: At 10x scale, localized human validation operational costs could breach our $5/user ceiling and trigger Thai PDPA data handling liabilities; we govern this via weekly 300-row Golden Dataset benchmark evaluations to stop model drift.
3. Competitive: The core advisory logic is highly vulnerable to foundational model commoditization; we will kill the project if onboarding drop-off during the manual OCR upload phase exceeds 80% within the first 1,000 sign-ups, proving the friction outweighs the value.

**The ask:**
We require $50,000, 2 Engineers, and 1 Part-Time Domain Expert for a 3-month horizon to ship the data ingestion layer and validate the unit economics, which requires pausing the Horizon 3 automated rate-scraper exploration.




## M1 Baseline vs. Now
*Your 3-sentence AI strategy from Module 1 vs. what you'd say now:*

**M1 baseline:**

**Now:**
