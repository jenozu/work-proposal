# Shipping + SAP delivery — preliminary time study

## Timed current workflow and proposed target

| Step | Current handling estimate |
|---|---:|
| Purolator shipment creation and label printing | **30 sec** |
| SAP Business One delivery creation and printing | **45 sec** |
| **Total** | **75 sec/shipment** |
| Proposed assisted workflow **target** | **10–15 sec/shipment** |
| Potential time reduction **if target achieved** | **60–65 sec/shipment** |
| Percentage reduction against 75 sec | **80.0–86.7%** |

New assisted workflow: supply SO number, package weight, dimensions, and shipment type when relevant; system retrieves order details, produces Purolator label, creates SAP delivery and prints both via supported approved interfaces. Verify serial numbers, address, order line mapping and exceptional cases before posting.

## Annual shipping scenario (not a measured annual volume)

Assume **250 workdays** and average **5–10 shipments per day** for illustration.

| Assumed shipments per working day | Annual shipments | Hours released at 60 sec | Hours released at 65 sec |
|---:|---:|---:|---:|
| 5 | 1,250 | 20.8 | 22.6 |
| 10 | 2,500 | 41.7 | 45.1 |
| 15 (peak comparison only) | 3,750 | 62.5 | 67.7 |

The proposal uses approximately **21–45 hours/year** for the 5–10/day scenario, not the 15/day peak. At **1,000 shipments**, the conditional range is **16.7–18.1 hours**.

Busy-day throughput, fewer repeated entries and avoidance of corrections may matter beyond simple hours released; these are **not separately monetized**. Do not equate this directly with staff cost cuts.

## Pilot controls

Time representative shipments end-to-end. Include normal, multi-line, serialized, international/exceptional where relevant, voided and failed transmissions. Require correct labels, tracking, SAP quantities, delivery references and print completion before treating a trial as successful. Measure process operator handling and total system response separately.

Source: October 2026 direct observation (30s and 45s) and derived calculation.
