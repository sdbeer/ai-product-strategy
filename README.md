# Ai Product Strategy

> We are building ClearNee, an AI-native personal debt manager for overwhelmed Thai multi-creditor debtors that automates fragmented financial data ingestion and execution, because skyrocketing household NPLs coupled with a total lack of Open Banking infrastructure create a critical window for a hyper-local, workflow-driven financial savior.


---

## Strategy at a Glance

| Component | Module | Status | Key Artifact |
|-----------|--------|--------|-------------|
| **The Bet** | M1 | [x] | `01-the-bet/` |
| **The Moat** | M2 | [x] | `02-the-moat/` |
| **The Margin** | M3 | [x] | `03-the-margin/` |
| **The Contract** | M4 | [x] | `04-the-contract/` |
| **The Guardrails** | M5 | [x] | `05-the-guardrails/` |
| **The Pitch** | M6 | [x] | `06-the-pitch/` |

---

## The Bet (M1)

**What we're building, for whom, why now.**

- **Product:** ClearNee — AI Personal Debt Manager
- **AI Value Archetype:** Copilot
- **Vulnerability Scores:** _(add: Moat 3/5 · Data 2/5 · Platform 3/5)_
- **Top Risk:** The manual OCR-onboarding friction creates a massive growth bottleneck, while the core AI advisory logic is highly vulnerable to being replicated by commoditized foundational LLMs
- **Confidence:** M
- **Prototype:** https://clearnee-copilot.lovable.app
- **Kill Criteria:** We will kill the project if onboarding drop-off during the manual OCR contract upload phase exceeds 80% within the first 1,000 sign-ups, proving that the user's financial pain is insufficient to overcome the friction of fragmented data ingestion.

→ Details: [`01-the-bet/`](01-the-bet/)

---

## The Moat (M2)

**Why this won't get copied in 6 months.**

- **Data Flywheel Score:** 9/20 
- **Weakest Loop:** Corrections Loop, Domain Context Loop, Network Loop
- **Top Encroachment Threat:** Big Tech Foundation Models (e.g., OpenAI, Google).
- **Encroachment Defense:** Corrections Loop Fix: Implement an automated pipeline that anonymizes user OCR corrections and feeds them into a nightly fine-tuning loop, making ClearNee’s proprietary text-extraction engine progress…
- **Vendor Portability:** _(add: Ready / Partial / Locked)_

→ Details: [`02-the-moat/`](02-the-moat/)

---

## The Margin (M3)

**Will this make money or bleed it?**

- **Gross Margin (current):**
- **Gross Margin (AI-adjusted):**
- **Pricing Model:**
- **Pricing Today → Tomorrow:**
- **Total AI COGS / unit:**
- **Cascading Strategy:** Triage: Small tier model (e.g., Gemini Flash) acts as the gateway router.; frontier: Premium reasoning model (e.g., OpenAI o1 or equivalent).; ratio 90% (Small/Mid) / 10% (Frontier).
- **Net Margin Shift:** - $\Delta$ margin %: +42.3% , $\Delta$ gross $: +$11.00 per user/month (Profit jumps from $8.50 to $19.50)
- **Break-even at:**

→ Details: [`03-the-margin/`](03-the-margin/)

---

## The Contract (M4)

**Why users will trust a probabilistic system.**

- **Reliability Target:** 95%
- **Golden Dataset:**
- **Confidence UX:** Tiered confidence with a source evidence panel for scanned contracts, paired with a mandatory human-in-the-loop validation trigger before final document submission.
- **HITL Architecture:** **Trigger:** Confidence <92% OR safety rubric flag fires on a customer-facing output.
- **Failure Mode Coverage:** *What failure mode did your partner find that you missed?*

→ Details: [`04-the-contract/`](04-the-contract/)

---

## The Guardrails (M5)

**What breaks when this scales — and what compounds.**

- **Compounding System:** | Loop | Input | Output | Compounds? | Status | |------|-------|--------|-----------|--------| | Recursive Learning | User-initiated OCR line-item overrides and manual text corrections when the system misreads interest r…
- **Governance Posture:** Automated Document Ingestion: The data privacy, extraction fairness, and reliability constraints of the multi-page Thai legal contract OCR scanning and text-parsing engine.
- **Autonomy Boundaries:** Sending routine repayment reminders & interest rate shift alerts — auto. Formulating optimized repayment schedules (Avalanche vs. Snowball roadmaps) — human approval required.…
- **Escalation Triggers:** 1. Ingestion Confidence Score drops below 92% 2. Conversational response sentiment analysis flags distressed or extreme language 3. User makes a direct legal or formal exception query 4.…
- **Audit Cadence:** Weekly — 300-Row Golden Dataset Evaluation. We pass current production prompts through our benchmark to check for sudden statistical regressions in extraction accuracy (rule-based code) and safety/hal…
- **Shadow AI Audit (user-side):**
- **Agent Boundaries:** Market Intelligence Scraper — can continuously scrape public Thai retail bank websites for fluctuating interest rates and government debt-relief updates; cannot modify active customer strategies or inject data into user profiles directly.…
- **Regulatory Exposure:** Thailand PDPA (Personal Data Protection Act): Outlines data processing requirements, data subject rights (access/deletion), and the 72-hour automated data breach reporting window.

→ Details: [`05-the-guardrails/`](05-the-guardrails/)

---

## The Pitch (M6)

**How you get this funded, shipped, and adopted.**

- **Horizon 1 (Now):** **5. Integrate Third-Party OCR API** · **7. Implement Basic OpenAI API Integration** · **10. Deploy Localized ThaiQR Payment rails** · **1. Data Ingestion Layer (OCR)**
- **Horizon 2 (Next):** **3. Confidence UX & Control Surfaces** · **6. Build Split-Screen Interactive Override Panel** · **8. Architect Model Cascading Router** · **9. Design 'Capped Hybrid' Plan Gate** · **12. Create Emergency Human Validation Queue** · **2. Advisory Engine & Cost Curve Optimization**
- **Horizon 3 (Bet):** **4. Governance & Operational Infrastructure** · **11. Setup 300-Row Golden Dataset Evaluation Matrix** · **13. Configure Automated Prompt Version Rollback** · **14. Build Automated Web Scraper for Thai Bank Rates**
- **Board Narrative:** ClearNee captures the surging Thai debt advisory market by using an automated document-processing workflow to bypass the country's lack of Open Banking, turning fragmented loan contracts into optimized repayment roadmaps.
- **Ask:** We require $50,000, 2 Engineers, and 1 Part-Time Domain Expert for a 3-month horizon to ship the data ingestion layer and validate the unit economics, which requires pausing the Horizon 3 automated rate-scraper exploration.
- **Key Strategic Change:**

→ Details: [`06-the-pitch/`](06-the-pitch/)
