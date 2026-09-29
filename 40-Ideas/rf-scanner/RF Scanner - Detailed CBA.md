---
type: cost-benefit
status: draft
created: 2026-09-24
updated: 2026-09-29
confidence: mixed
tags:
  - rf-scanner
  - analysis
---

# RF Scanner + Shipping Automation — Detailed Working CBA

**Scope:** Combined RF warehouse application and planned Purolator shipping integration. Proposed **30-day pilot**, conditional on management approval and SAP test-server access. No automated shipping savings have yet been observed.

## 1. Evidence register and inputs

| Input | Current working value | Evidence quality |
|---|---:|---|
| SAP shipment documents over approximately two years | 6,174 | Observed screenshot from SAP query, exact filters still to review |
| Annual average based on two-year window | 3,087 | Calculated: 6,174 ÷ 2 |
| Average shipment documents per active shipping date | 12.5 | Calculated by SAP query |
| Estimated proportion sent via Purolator | 90% | Employee estimate; verify via SAP carrier or Purolator records |
| Estimated eligible Purolator shipments annually | 2,778.3 (≈2,778) | Calculated: 3,087 × 90%; assumes 1 document = 1 eligible shipment |
| Current manual handling per shipment | About 3 min | Employee estimate, to time directly |
| Minutes eliminated by automation | Unknown; model 1, 2 and 3 min | Scenario only; 3 min is theoretical maximum |
| Labour valuation | **$24/hour** | Employee's stated base wage, not fully loaded cost |
| Pilot duration | 30 days | Proposed, not approved |
| Integration licence | ~CAD $100/month, paid annually (~$1,200) | Employee's provisional quote; exact API/licence/terms unconfirmed |

**Query caution:** The screenshot counts distinct SAP DocEntry and distinct dates. Confirm whether it excludes cancellations, combines deliveries into one package, misses manual shipments or includes customer pickups and UPS. SAP document counts are a starting point, not automatically carrier transaction counts.

## 2. Shipping-module annual-value scenarios

General formula:

`Annual Purolator hours potentially released = (SAP annual shipments × eligible Purolator proportion × minutes truly eliminated) ÷ 60`

`Wage-equivalent capacity value = hours released × $24/hour`

| Minutes actually eliminated | Annual hours potentially released | Annual capacity value at base wage |
|---:|---:|---:|
| 1 min | 46.305 h | $1,111.32 |
| 2 min | 92.610 h | $2,222.64 |
| 3 min | 138.915 h | $3,333.96 |

The **2-minute scenario** is an illustration, not an observed outcome. It equates to about **7.7 h/month** and **$185.22/month** of wage-valued capacity. At 3 minutes, theoretical monthly released time is approximately **11.6 h**. Measure remaining physical packing, printing, exception handling and any manual reviews separately; time may not fall to zero.

Any reduction in manual shipment-notification emails belongs to the **Shipping Notifications** project unless that function is explicitly delivered as part of the integrated RF scope. Do not count the same action in two CBAs.

## 3. Other RF Scanner modules — awaiting baseline

| Workflow | Annual volume | Before time | Assisted time | Annual hours released |
|---|---:|---:|---:|---:|
| Inventory lookup | TBD | TBD | TBD | TBD |
| Picking, **including sorting** | TBD | TBD | TBD | TBD |
| Receiving and putaway | TBD | TBD | TBD | TBD |
| Inventory counting | TBD | TBD | TBD | TBD |

Previously published totals of **216 annual hours released**, derived from hypothetical activity frequencies/timings, were **never verified**. Do not include them in the current submission total until replaced with actual measurements. Avoid counting RF modules again as separate portfolio savings.

## 4. Costs and financial interpretation

The user has confirmed a **$24/hour base wage**. This provides a simple labour-capacity valuation, **not** an employer's fully loaded rate; payroll taxes, benefits and other overhead have not been quantified. Freed time is operational capacity rather than cash savings unless it leads to documented avoided overtime, replacement hiring or other actual expense.

**Provisional required spend:** SAP integration licence around **$1,200/year, paid annually**, dependent on the actual integration method and a written quotation. This may be an upfront annual cash commitment; check whether a test licence or existing entitlement is available before purchase.

**To confirm:** incremental development hours and whether undertaken on paid time; training and pilot time; hosting; maintenance/support workload; equipment; security and integration expenses. Earlier $3,560 remaining implementation, $420 hosting/integration and $1,440 maintenance estimates were placeholders and should **not** be used as current costs without evidence.

**Net annual operational value and payback: TBD.** Once the eligible workflows and realistic times are known, calculate gross wage-equivalent capacity; separately report any demonstrated cash savings and actual recurring costs. The shipping-only scenario is not a complete RF business case; do not infer full-system payback from it.

## 5. Proposed 30-day pilot evidence

Before starting: request management approval and SAP test-server access; verify carrier integration credentials, licence scope and permitted test data. Log a representative baseline for Purolator shipments and each in-scope RF module.

During approved testing, capture shipment creation/review/label-print times separately, successful and failed requests, mismatch/correction rates, and the same metrics for comparable manual runs. Include practical staffing effects and supported warehouse-module trials. Preserve identifiable business data only within approved company systems.

At the end, update this analysis with measured before/after savings, confirmed annual volume, incremental and operating costs, limitations and a decision on further implementation.

## 6. External business case — separate future investigation

Adaptation to other distributors could generate software-licence, implementation or support revenue only after verifying product readiness, legal/IP ownership, market interest, generalization costs and support obligations. Do not use hypothetical external sales to reduce internal payback.

## 7. Open decisions

Confirm actual Purolator percentage and shipment equivalence; precise 3-minute task boundaries; feasible automation time reduction; verified costs and entitlement to the integration licence; annual activity volumes and times for other RF modules; whether the pilot will include an end-to-end shipping integration.
