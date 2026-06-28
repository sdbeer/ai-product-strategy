# Cost Curve & Pricing Strategy

## Packaging decision

**Leader:** Centralized debt dashboard and core optimization strategy

**Filler:** Auto-generated repayment reminders and basic text summaries of bank notices

**Killer:** Auto-generating complex legal refinancing applications and running continuous multi-agent workflows to monitor shifting bank rates

**Killer usage %:** ~10%

**Bundle or add-on:** add-on


## Cost Model
- Avg requests/user/month: 50
- Blended cost/request: $0.2
- Revenue/user/month: $20
- Non-AI COGS/user/month: $1.5

## Current Margin
- AI COGS/user: $10.00
- Total COGS/user: $11.50
- Gross margin: 42.5% ($8.50/user)

## Cascading Strategy
<!-- Cheap model → frontier model routing logic -->

**Triage model:**
Small tier model (e.g., Gemini Flash) acts as the gateway router.

**Frontier model:**
Premium reasoning model (e.g., OpenAI o1 or equivalent).

**Routing rule:**
Evaluate incoming user intents. If a request is a routine chat or dashboard pull, execute immediately on the Small tier. If it requires cross-institutional debt calculation, cascade to Mid. If it contains a raw multi-page OCR contract payload, cascade to Frontier.

**Expected cascade ratio:**
90% (Small/Mid) / 10% (Frontier).

## Pricing Model

**Pricing Strategy**
- Strategy posture: Penetrate
- Pricing model: Hybrid (base + usage)
- Unit of work metered: contract scans processed
- Base fee ($/month): 20
- Price per unit: $1.50
- Estimated units/user/month: 2
- Implied revenue/user/month: $23.00

Decision Note
Why this pricing structure fits the buyer and the value delivered: A low $20 base fee eliminates adoption friction for financially stressed debtors while bundling baseline tracking. Charging $1.50 per extra scan directly aligns our pricing with heavy AI inference costs, preventing margin collapse.

## Stress Tests

| Scenario | AI COGS | Margin |
|----------|---------|--------|
| 3x Cost  | $30.00 | -57.5% ($-11.50) |
| 2x Usage | $20.00 | -7.5% ($-1.50) |

## Board One-Pager
<!-- Before/After: Old SaaS revenue vs. AI usage revenue for your product -->

**Before (traditional SaaS):**
**After (AI-enabled):**
**Net margin shift:**
