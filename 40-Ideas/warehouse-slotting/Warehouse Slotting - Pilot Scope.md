# Warehouse Slotting & Picking Optimization — priority project 4

**Status:** proposed pilot; no confirmed reduction target.

## Business problem
Frequent picking can require unnecessary walking when frequently requested products are stored away from packing/shipping. Location changes must preserve handling safety, aisle access and inventory accuracy.

## Method
1. Identify representative physical pick events and eligible sales-delivery and inventory activity.
2. Rank SKUs by **physical picking frequency**, not revenue, price or units sold alone. Investigate returns, duplicate lines, fulfilment modes and distinct picker visits.
3. Audit existing bin and aisle locations; measure distances along walkable routes to shipping.
4. Check each candidate SKU for dimensions, weight, lifting, fragility, safety and space restrictions.
5. Simulate current and proposed routes on representative order groups, then record physical times and distances.
6. Move a small reversible set of items only after warehouse management approves the pilot. Confirm location accuracy and remeasure the same work mix.

## Operational outcome
Seek lower non-value-added travel, stable pick accuracy and better order fulfillment time, while avoiding increased handling, replenishment or safety burden.

## Safeguards
Do not estimate an improvement percentage without before/after observations. Keep an explicit location rollback map; verify SAP bin changes through approved processes. Warehouse Operations owns acceptance; IT/SAP approves relevant data access.

This project replaces the earlier direct-ship project in the five priority proposals.
