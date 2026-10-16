# Project 1 — Automated Inventory Cycle Counting

## Current Challenge

Marindustrial's periodic annual inventory count requires approximately **four employees over two to three working days**, equivalent to roughly **64–96 employee-hours of direct counting** on an eight-hour-day assumption. More significant than this labour figure is the disruption to regular warehouse activities. Discrepancies identified only during an annual count can remain unresolved for months, reducing confidence in stock availability and increasing corrective work.

Historical SAP-based count-line accuracy was reported at **97.36% in 2023**, **94.72% in 2024** and **91.41% in 2025**. These are historical measures; the underlying count method and definition should be reconfirmed before management uses them as performance indicators. Initial analysis identified **3,833 stocked item records**, although item classes, active count eligibility and location scope require validation.

## Proposed Solution

Introduce **scheduled, guided ABC/risk-based cycle counting**, supported by SAP item and inventory data. Count frequency would respond to a combination of **inventory value, movement or annual sales activity, discrepancy history, and operational criticality**, rather than unit price alone. The system would assign a manageable daily set of items or locations, guide the count, temporarily control the affected area as needed, and record variances for authorized review before SAP adjustments.

A preliminary model suggested **approximately 15–20 minutes of physical counting per working day**, but this excludes variable investigation, administration, travel and reconciliation overhead. The final ABC formula and frequency plan should be calibrated on real SAP exports and physical test counts; provisional categories are **not** final production rules.

## Expected Benefits

- Potentially reduce or eliminate the need for a disruptive multi-day annual count, **subject to Finance/audit approval and proven accuracy**.
- Detect discrepancies closer to when they arise.
- Improve inventory reliability and support more consistent receiving and picking.
- Distribute counting activity over the year instead of concentrating it in a shutdown period.

## Pilot & Evaluation

Select representative high- and low-activity items and locations. Measure actual count time, preparation, stock-area controls, investigations, exception handling, schedule completion and reconciliation accuracy. Evaluate whether routine operations can continue safely during counting and what level of annual physical verification remains required. A new programme may use **equal or greater total labour** than annual counting; net payroll savings are not assumed.

**Primary objective:** Improve inventory accuracy and operational continuity through routine, controlled verification—not simply minimize counting minutes.

Supporting evidence: [Inventory cycle-counting research](../../evidence/inventory-cycle-counting.md).
