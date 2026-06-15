# Three-Axis Vulnerability Diagnostic

## Product
<!-- Name the product you're diagnosing. Real product at your company — not a hypothetical. -->


**Product: AI Personal Debt Manager**
**Your Role: PM**

---

## Scores

### Contextual Moat — _4_/5
*Workflow depth × switching cost. Would users leave in a weekend if a competitor showed up?*

**Score rationale:**
The application automates the full lifecycle. It initiates refinancing applications with local Thai banks, executes payday smart routing according to the optimized debt-clearing strategies, and routes transactions via local gateways. The switching cost is not just historical data. It is the immense operational friction a user faces when disconnecting a live system that actively manages, saves, and optimizes their actual money.

**Named attacker (from partner challenge):**

---

### Data Advantage — _4_/5
*Proprietary signal that compounds with usage. What do you see that OpenAI doesn't?*

**Score rationale:**
The product tracks anonymous, non-public settlement negotiation success rates and concession behaviors with specific local Thai banks. As more users negotiate debts through the platform, the AI learns exactly which terms individual banks accept under specific conditions, creating a compounding, legally and technically protected data edge.

**Named attacker (from partner challenge):**

---

### Platform Exposure — _4_/5
*Encroachment risk × pivot speed. If Apple/Google/OpenAI ships your hero feature native — then what?*

**Score rationale:**
Our core product features a complex, automated operational loop deeply integrated with localized Thai payment infrastructure, local bank APIs, and proprietary negotiation flywheels. Generic tech platforms cannot easily copy this highly regionalized execution layer, nor do they care to target it.


**Named attacker (from partner challenge):**

---

## Top Vulnerability
<!-- One line: what's the single biggest strategic risk? -->
Its heavy dependence on local Thai banks and creditors, who could choke the automated workflow by delaying APIs, restricting payment access, or resisting automated settlements.


## Confidence Level
<!-- H / M / L — how confident are you in this bet after the diagnostic? -->
M
