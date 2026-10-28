# Management Reporting & BI Dashboard — Build Plan

**Status:** Planning / proposal prototype  
**Updated:** 2026-10-28  
**Purpose:** Capture the dashboard concept discussed on 2026-10-21 so the proposal can be continued without losing requirements.

## Goal

Build a management-facing dashboard prototype that turns SAP Business One sales, inventory, purchasing, customer, and operations data into useful decisions rather than static reports. The prototype should demonstrate what management could see, what questions it could answer, and how the reporting layer could generate practical recommendations.

For the proposal/demo, use clearly labelled hypothetical sample data. Do not place real customer names, prices, costs, margins, or other confidential company data in the public repository.

## Dashboard Sections

### 1. Executive Overview

A high-level management landing page showing the most important business indicators at a glance.

Example measures:
- Revenue and gross profit
- Gross margin
- Order / invoice volume
- Top products and customers
- Inventory value and stock-risk indicators
- Sales trend versus prior period
- Operational exceptions that require attention

The purpose is not to maximize the number of KPIs. It is to make the most important changes, risks, and opportunities visible quickly.

### 2. Product Performance — 80/20 Analysis

A core section of the prototype.

The dashboard should rank SKUs separately by:
1. Revenue contribution
2. Gross-profit contribution

It should calculate cumulative contribution and identify the small group of products responsible for approximately 80% of revenue and/or gross profit. Do not assume the exact result will always be 20% of SKUs; the dashboard should calculate the actual concentration from the data.

Suggested views:
- Top products by revenue
- Top products by gross profit
- Cumulative Pareto chart
- Revenue share vs. profit share
- Units sold / order frequency
- Customer count per SKU
- Trend by month
- Products with strong revenue but weak margin
- Products with strong margin but low sales penetration

This section should help answer: **Which products matter most, why do they matter, and what can Marindustrial do to sell more of them profitably?**

### 3. Customer Purchasing Patterns

Analyze transaction history to identify repeatable purchasing relationships.

Examples:
- Products commonly purchased together
- Customers who buy a primary product but not its common secondary / supporting products
- Repeat-purchase intervals
- Customer-specific product preferences
- High-value customers and their product mix
- Customers whose purchasing activity has declined
- Products with cross-sell potential based on similar customers

The output should lead to testable sales opportunities rather than simply describing historical behavior.

### 4. Bundle & Offer Lab

Translate product and customer analysis into candidate offers management or sales can review.

Example recommendations:
- Bundle a high-performing primary item with commonly purchased secondary parts
- Offer a modest discount on secondary parts when purchased with the primary item
- Quantity discounts where purchase history supports them
- Target customers who regularly buy Product A but rarely buy the related Product B
- Create account-specific or segment-specific offers based on prior purchase patterns

Each recommendation should show the evidence behind it where possible, such as purchase frequency, customer count, revenue/profit contribution, and historical product affinity.

These are **recommendations for testing**, not automatic pricing decisions.

### 5. Inventory & Purchasing

Connect sales performance with inventory decisions.

Potential views:
- On-hand inventory
- Inventory value
- Fast / slow movers
- Stockout or low-stock risk
- Excess inventory
- Days since last sale
- Demand trend
- Purchase / replenishment indicators
- High-value products requiring closer attention

This section should eventually complement the automated cycle-counting and warehouse projects in the broader proposal.

### 6. Shipping & Operations

Provide operational visibility alongside financial reporting.

Potential measures:
- Orders / shipments processed
- Shipment volume trends
- Carrier activity
- Shipping exceptions
- Processing-time measurements where reliable data exists
- Receiving / warehouse activity as data becomes available

The prototype should only display metrics supported by available source data and should avoid invented savings.

### 7. Reports & Recommendations

Allow the dashboard analysis to be converted into a concise management report.

A generated report could summarize:
- Major changes since the previous period
- Top revenue and profit drivers
- Products requiring attention
- Inventory risks
- Customer opportunities
- Cross-sell / bundle candidates
- Suggested follow-up actions

The goal is to move from **data → analysis → recommendation → management action**.

## Sample Data Requirements

Create synthetic/demo data sufficient to demonstrate the dashboard without exposing company information.

Minimum logical datasets:
- Products / SKUs
- Customers
- Sales documents and line items
- Quantity sold
- Revenue
- Cost / gross profit
- Transaction dates
- Inventory on hand
- Product category or family
- Purchase history relationships
- Optional purchasing and shipping fields where needed for prototype views

Sample data should be internally consistent so that calculations and recommendations can be demonstrated credibly.

## Calculation Rules

- Revenue and gross profit rankings must remain separate.
- Pareto analysis should sort products by the selected metric, calculate cumulative contribution, and determine the actual SKU share required to reach roughly 80%.
- Gross profit should be based on revenue minus the applicable product cost in the demo dataset.
- Recommendations should be traceable to measurable patterns in the sample data.
- Demo numbers must be labelled hypothetical and must not be presented as verified Marindustrial results.
- Avoid unsupported ROI or savings claims. The pilot should establish baselines before financial benefits are stated as facts.

## Build Tasks

### Phase 1 — Data Model
- Define synthetic product, customer, sales, inventory, and purchasing datasets.
- Create enough transaction history for meaningful trends and product-affinity examples.
- Document field definitions and calculation assumptions.

### Phase 2 — Core Dashboard
- Build Executive Overview.
- Build Product Performance / Pareto analysis.
- Build revenue and gross-profit rankings separately.
- Add filtering by date, product/category, and customer where useful.

### Phase 3 — Commercial Analysis
- Build Customer Purchasing Patterns.
- Identify commonly purchased product combinations.
- Identify cross-sell gaps.
- Build Bundle & Offer Lab with evidence-backed suggestions.

### Phase 4 — Operations
- Add inventory / purchasing views.
- Add shipping / operations views where source data supports them.
- Connect dashboard concepts to the cycle-counting, slotting, RF scanner, and shipping pilots where relevant.

### Phase 5 — Reporting
- Generate a management-friendly summary from dashboard findings.
- Surface prioritized opportunities and exceptions.
- Make recommendations explainable and traceable to the underlying metrics.

## Prototype Completion Criteria

The prototype is successful when it can demonstrate, with hypothetical data:

- Which products generate the largest share of revenue.
- Which products generate the largest share of gross profit.
- The actual product concentration required to reach approximately 80% of each metric.
- Which products are frequently purchased together.
- Which customers have identifiable cross-sell opportunities.
- At least several evidence-backed bundle, secondary-part discount, or quantity-discount ideas.
- Inventory / operational exceptions that management could act on.
- A concise report that converts dashboard findings into suggested actions.

## Proposal Positioning

This dashboard is part of the **Centralized Reporting & Automated BI** pilot. Its value is not merely replacing spreadsheets with charts. The intended capability is a reusable internal reporting layer that can combine SAP and operational data, reduce manual report preparation, expose business patterns that are difficult to see manually, and support better sales, inventory, purchasing, and operational decisions.

The prototype should demonstrate capability first. Real Marindustrial data, final KPI definitions, validated baselines, and production integration would be handled during an approved pilot.
