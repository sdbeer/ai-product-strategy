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

**Scope:**
**Autonomy boundaries:**
**Escalation triggers:**
**Audit cadence:**
**Regulatory exposure (EU AI Act / other):**

## Agent Topology
<!-- If using agents: what can each agent do? What can't it do? Who approves what? -->

## Shadow AI Audit

| Tool | Owner | Risk Level | Decision |
|------|-------|-----------|----------|
| | | H / M / L | keep / govern / kill |
| | | H / M / L | keep / govern / kill |
| | | H / M / L | keep / govern / kill |

**Total tools found:**
**Tools after triage:**
**Estimated hidden spend:**
