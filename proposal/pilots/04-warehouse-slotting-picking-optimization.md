# Project 4 — Warehouse Slotting & Picking Optimization

## Current Challenge

Inventory locations in the Mississauga warehouse are influenced by product size, available storage and previous placement decisions. Some frequently picked items may be farther from the shipping and packing area than is operationally necessary. Because workers walk to retrieve products for multiple sales orders, even small unnecessary distances can add up over a working day. Any changes must preserve safe handling of large engines, PTOs, heavy parts and small components.

## Proposed Solution

Analyze **how often items are physically picked from warehouse locations** and recommend locating the most frequently picked products in the nearest suitable bins to shipping. Less frequently picked products could occupy more distant storage when size, capacity, handling equipment and accessibility allow. Use a warehouse distance map to compare present pick routes with proposed placements. The system would **recommend**, not automatically implement, inventory relocation.

## Preliminary Analysis

Approximately **five years of SAP sales, delivery, purchasing and inventory-movement history**, combined with bin-location records, can provide candidate evidence. However, sales revenue and total quantity shipped do **not** measure how many times a worker physically visits a bin. Direct shipments fulfilled by other branches, cancellations, returns, non-stock transactions and other nonlocal movements must be excluded or classified correctly. Actual physical-pick concentration should be calculated rather than assuming an 80/20 distribution.

Earlier exploratory warehouse work included a graph of nodes and travel edges and representative orders with different numbers of lines. That work demonstrates a possible simulation approach, **not a verified walking-distance reduction**. Reliable recommendations require validated locations, realistic route constraints and sample orders.

## Expected Benefits

Optimized placements may shorten average walking distance and pick-to-stage time, reduce fatigue and increase available picking capacity. These outcomes are **hypotheses**, not guaranteed percentages or financial savings. Any gain must be weighed against physical relocation effort, disrupted operations, storage capacity and potential congestion.

## Pilot & Evaluation

Build a verified current-location map. Calculate local physical-pick frequency from cleaned historical transactions. Simulate identical representative orders under current and proposed layouts, then seek approval for a limited, reversible relocation trial. Record walking distance, complete picking time, accuracy, relocation person-hours, access/safety constraints and operator feedback. Attribute placement-related walking gains here, **not again** to the RF Scanner pilot.

## Primary Objective

Use verified picking patterns to reduce avoidable warehouse travel while protecting safety, accuracy and practical stock accessibility.

Supporting evidence: [slotting analysis plan](../../evidence/warehouse-slotting.md).
