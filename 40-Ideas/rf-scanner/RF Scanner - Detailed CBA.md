---
type: cost-benefit
status: draft
created: 2026-09-24
updated: 2026-09-24
confidence: estimated
tags:
  - rf-scanner
  - analysis
---

# RF Scanner — Detailed Cost-Benefit Analysis

**Working example only.** Figures below are placeholders to be replaced by pilot measurements. Existing work is a sunk investment for the go-forward payback; a separate whole-project historical-cost view may be prepared if management requests it.

## 1. Scope
Evaluate four observable workflows: inventory lookup; full picking cycle including wave sorting; receiving plus putaway; and inventory counting. Record quality as well as speed. Other planned product features are outside this initial benefit estimate.

## 2. Baseline model (illustrative)
Assume 240 applicable working days per year. A volume is the **total annualizable activity across the users in scope**, not a per-employee number to multiply again.

| Task | Total tasks/day | Before min | After min | Hours released/year |
|---|---:|---:|---:|---:|
| Inventory lookup | 12 | 3 | 1.5 | 72 |
| Picking (including sorting) | 10 | 9 | 7 | 80 |
| Receiving / putaway | 3 | 15 | 11 | 48 |
| Counting | 1 | 20 | 16 | 16 |
| **Total** | | | | **216** |

For each task: `(before minutes - after minutes) × total tasks/day × 240 ÷ 60`.
Do not treat RF submodules as independent savings when the parent RF CBA already includes them.

## 3. Annual internal value (illustrative)
- Hours released: `216`
- Fully loaded labour assumption: `$30/hour` — requires verification
- Capacity value: `216 × 30 = $6,480`
- Usable-capacity factor: `75%` — requires validation
- Usable capacity value: `$6,480 × 75% = $4,860`
- Hosting/integration allowance: `$420/year`
- Maintenance allowance: `$1,440/year`
- **Annual net operational value: `$4,860 − $1,860 = $3,000`**

**Accounting distinction:** This is opportunity/capacity value, not guaranteed cost savings. Separately track avoided overtime, external software, errors and truly avoidable spending. Never add the same released capacity twice.

## 4. Incremental implementation estimate
- Remaining development: `80 × $40 = $3,200`
- Training/testing: `12 × $30 = $360`
- Additional equipment: `$0` assumed, verify
- **Initial remaining investment: `$3,560`**
- **Steady-state payback: `$3,560 ÷ ($3,000 / 12) = 14.24 months`**

Payback begins only when benefits actually start; the ramp-up period may extend calendar payback. Maintenance time and testing time must not be counted twice.

## 5. Internal process quality (initially unpriced)
Log lookup correctness, receipt variance, picking errors and final sorting issues, recounts, adoption, uptime and user feedback. Price only benefits supported by observed rates and attributable costs.

## 6. Internal vs external comparison
Internal development may have a lower **remaining** cost than commissioning comparable custom work externally, particularly because a prototype exists. Do not claim a measured price advantage without formal like-for-like external quotations that include integration, training, ongoing support, hosting, ownership and maintenance.

## 7. External commercial scenario — NOT internal value
Assume only for illustration: five customers, $250/month subscription and $1,500 implementation. Full-year recurring gross revenue `5 × 250 × 12 = $15,000`; setup gross revenue `5 × 1,500 = $7,500`. Combined gross first year **$22,500** only if all customers sign at start and remain for 12 months. No support, generalization, hosting, acquisition or tax costs included. Do not label this profit or forecast.

## 8. Key risks and controls
- SAP data freshness / permitted integration: validate.
- Inventory consistency and concurrency: test before relying on movements.
- User adoption: include training and real-user trials.
- Scope creep: advanced features are not a prerequisite for the MVP.
- External rights: resolve ownership/IP and data/privacy permissions before commercialization.

## 9. Measurement plan
See [[RF Scanner - Pilot Test Plan]] and [[60-Day Pilot Plan]]. Baseline and assisted samples should use comparable order complexity, routes, employees and workloads. Record unsuccessful trials too.

## 10. Open data
Actual activity volumes, loaded hourly rate, before/after distributions, maintenance hours, hardware needs, external quotes and adoption ramp: **TBD**.
