# Compounding System Design

## Feedback Loops

| Loop | Input | Output | Compounds? | Status |
|------|-------|--------|-----------|--------|
| Recursive Learning | User-initiated OCR line-item overrides and manual text corrections when the system misreads interest rates or loan terms from scanned Thai banking documents. | Validated, anonymized correction pairs formatted as updated golden dataset rows to expand our custom evaluation benchmarks. | N | missing |
| Cross-Domain Transfer | Multi-creditor repayment settlement patterns, behavioral negotiation timelines, and successful haircut percentages achieved in the consumer debt vertical. | Pre-trained semantic prompt structures, predictive negotiation playbooks, and alternative risk profiles applied directly to small-business (SME) micro-loan renegotiations. | Y | missing |
| Network Intelligence | Anonymized, aggregated platform-wide interaction metrics, counter-offer response times from specific banks, and final settlement friction points across the entire user fleet. | Global predictive intelligence models that automatically forecast a creditor's exact bottom-line settlement threshold and optimal negotiation timeline for any new user entering the platform. | Y | missing |

**Broken loop identified by partner:** Recursive Learning — User OCR corrections update localized dashboard profiles but never make it back to the centralized golden dataset to retrain or fine-tune our text-extraction prompts.
**Fix plan:** Introduce a UI thumbs-down flag -> auto-generate a data-patch ticket -> route code anomalies to a weekly golden-set audit pipeline owned by the on-call Product Manager.

## Context Connectivity
<!-- How does knowledge flow across teams and domains? Where does it silo? -->

**How knowledge flows:** Customer support tickets -> line-item override logs -> product analytics, but recurring document extraction errors do not reach the AI prompt engineering team.

**Where it silos:** Bank partnership objections never reach product development. Manual customer interest-rate correction logs sit in Zendesk or support database silos only.

## Governance Policy

**Scope:** Automated Document Ingestion: The data privacy, extraction fairness, and reliability constraints of the multi-page Thai legal contract OCR scanning and text-parsing engine.
Advisory Core Reasoning: Guardrails governing the generative outputs of AI-native debt optimization advisor, specifically relating to repayment schedules (Avalanche vs. Snowball), local Thai financial regulation compliance, and government debt-relief matching.
Automated Document Drafting: The security and validation frameworks for auto-generated legal refinancing files and bank applications.
User Communication Layer: Direct text outputs regarding automated dashboard insights, conversational financial chat answers, and proactive repayment alerts or reminders. Excludes: Traditional Transaction Infrastructure: Traditional localized transaction execution, merchant-side processing, and payment rails (e.g., ThaiQR, mobile banking deep-linking, or PSP direct debits), which are governed under separate standard financial security and compliance frameworks.
Static External Web Scrapers: The basic software code scripts used to pull public bank interest rates and program updates from external websites (separate data-harvesting policies apply).
Internal Analytics Dashboards: Static, non-AI business intelligence views used by the internal team to monitor general corporate metrics (e.g., user sign-ups or billing status).

**Autonomy boundaries:** Sending routine repayment reminders & interest rate shift alerts — auto. Formulating optimized repayment schedules (Avalanche vs. Snowball roadmaps) — human approval required. Drafting formal bank refinancing and debt consolidation applications — human approval required. Setting up direct banking deep-links or executing ThaiQR money transfers — never auto.

**Escalation triggers:** 1. Ingestion Confidence Score drops below 92% 2. Conversational response sentiment analysis flags distressed or extreme language 3. User makes a direct legal or formal exception query 4. Explicit human intervention requests or consecutive rejections

**Audit cadence:** Weekly — 300-Row Golden Dataset Evaluation. We pass current production prompts through our benchmark to check for sudden statistical regressions in extraction accuracy (rule-based code) and safety/hallucination rates (LLM-as-Judge). (Lead PM). Monthly — Prompt-to-Output Semantic Distance & Drift Velocity. We measure whether background model optimizations from OpenAI have altered our advisory tone, localized legal compliance, or mathematical output stability. (Lead AI Engineer). Quarterly — Ground-Truth Refreshes & Failover Verification. We update our Golden Dataset with new Thai retail banking terms, update interest rate criteria, and execute a live provider failover drill in our staging environment to verify our Abstraction Layer's response speed. (Head of Product Strategy).

**Regulatory exposure (EU AI Act / other):** Thailand PDPA (Personal Data Protection Act): Outlines data processing requirements, data subject rights (access/deletion), and the 72-hour automated data breach reporting window.

Bank of Thailand (BOT) Guiding Principles for AI Risk Management: Enforces the "FEAT" structural protocol (Fairness, Ethics, Accountability, and Transparency) for financial models.

Thailand Computer-Related Crime Act (CCA): Restricts the digital ingestion and hosting of false, corrupted, or ungrounded generative data.. Risk tier: high. Controls: Prohibitive Model-Training Data Clauses: Strict data-processing agreements (DPAs) signed with downstream infrastructure vendors (e.g., OpenAI API) ensuring uploaded multi-page Thai debt contracts are never used to train foundational public weights.

Granular Sensitive Data Minimization: Algorithmic regex filtering protocols that scrub national ID numbers, birth dates, and unneeded personal metadata from raw contract text before passing the text payload to cloud-hosted LLM endpoints.

Explainable Evidence Tracking (Transparency Controls): A distinct visual "Evidence Panel" embedded directly within the user UI, displaying exact baseline interest rates and principal data matches alongside source clauses to comply with the BOT's AI transparency guidelines..

## Agent Topology
<!-- If using agents: what can each agent do? What can't it do? Who approves what? -->

Market Intelligence Scraper — can continuously scrape public Thai retail bank websites for fluctuating interest rates and government debt-relief updates; cannot modify active customer strategies or inject data into user profiles directly. Approval: Lead PM.

Debt Optimization Strategist — can calculate multi-creditor repayment roadmaps and auto-generate structured bank refinancing file formats; cannot execute transactional mobile banking deep-links or independently authorize real fund transfers. Approval: Dedicated Thai Financial Specialist.




## Shadow AI Audit

| Tool | Owner | Risk Level | Decision |
|------|-------|-----------|----------|
| | | H / M / L | keep / govern / kill |
| | | H / M / L | keep / govern / kill |
| | | H / M / L | keep / govern / kill |

**Total tools found:**
**Tools after triage:**
**Estimated hidden spend:**
