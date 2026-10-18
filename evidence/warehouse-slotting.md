# Warehouse Slotting & Picking Optimization — Research and Measurement Plan

**Status:** Candidate historical analysis and pilot design; no verified walking improvement or annual savings.

## Goal

Test whether locating frequently **physically picked** stock in nearby *suitable* bins can reduce warehouse walking and full pick-to-stage time. Revenue, unit value and total units sold are **not** substitutes for how often a worker must visit a bin.

## Candidate sources

- Up to five years of SAP sales/delivery history and inventory movements, joined carefully to local warehouse fulfillment.
- Bin and stock locations, physical size/weight, rack capacity, handling and safety constraints.
- Warehouse nodes and edges (measured layout distances), entry/packing depot and blocked paths.
- Representative in-stock pick orders across **1–2**, **3–5**, **6–10** and **10–15+** line groupings.

**Data cleaning:** Exclude or classify direct-ship/interbranch orders fulfilled elsewhere, cancelled orders, returns, non-stock lines, duplicates and transactions without a local pick. Account for stockouts, multiple orders combined into one visit and movements that are not customer picking. State exactly how 'one physical pick' is defined. Do not assume a Pareto 80/20 outcome.

## Pilot analysis

1. Validate period, active local warehouse scope, bin coordinates and product handling restrictions.
2. Calculate physical picking frequency and inspect distribution, rather than ranking items by dollar value.
3. Build a constrained slotting recommendation, respecting space, size, weight, access and grouped engines/PTOs.
4. Simulate identical representative orders in the current and proposed placements using a reproducible distance matrix.
5. With approval, trial a limited reversible move and measure walking, complete picking time, accuracy, congestion and relocation person-hours.
6. Estimate net value only after measured time changes and costs. Separate location/walking savings from RF interface benefits.

**Key measures:** metres/feet walked per order, elapsed pick-to-stage time, picking errors, relocation time and disruption, congestion, employee feedback, exception rates and support burden.

Historic SAP exports or layout prototypes are **inputs to be verified**, not proof of optimization. Never publish raw inventory/transaction records in this public repository without employer authorization.
