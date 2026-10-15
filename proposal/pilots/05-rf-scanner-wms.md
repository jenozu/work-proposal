# Project 5 — RF Scanner & Warehouse Management System

## Current Challenge

SAP Business One serves as the company's system of record for inventory, purchasing and sales. However, everyday warehouse tasks often require employees to locate orders, navigate desktop screens, look up item details, check quantities, confirm locations and re-enter transaction information. The fragmented steps become more noticeable during periods of heavy receiving and outgoing orders.

## Proposed Solution

Expand the **existing internally developed web-based RF scanner application** into a practical, mobile-friendly warehouse interface using barcode scanners and supported mobile devices. Priority pilot workflows include:

- **Receiving and GRPO:** retrieve purchasing documents, scan items and validate received quantities.
- **Sales-order picking:** retrieve lines, confirm item/barcode and quantity, and prepare accurate deliveries.
- **Inventory lookup:** locate items and view approved quantities or bin information without repetitive SAP navigation.
- **Staging and status:** show which picked orders are ready to ship and record their movement through the warehouse.
- **Inventory movement verification:** document exceptions and assist controlled warehouse transactions.

Integration must be scoped to available permissions and supported SAP methods. Existing code demonstrates a development starting point; **not every listed module is confirmed production-ready**. Verify the actual repository and workflow behaviour before deployment claims.

## Expected Benefits

Potential benefits include faster receiving and picking, fewer item or quantity errors, improved order visibility, reduced time searching for information and a more consistent warehouse process. These benefits can improve warehouse capacity without automatically changing staffing.

## Pilot & Evaluation

Use typical order sizes and receiving tasks, including exceptions. Compare **complete** manual versus assisted workflows—not merely screen interaction—including walking, sorting, scanning, verification, corrections and SAP completion. Track time per task, accuracy, user adoption and maintenance requirements. Attribute inventory counting improvements to **Project 1** and carrier/SAP shipping administration to **Project 3**, so this project's financial benefit includes only distinct receiving, picking, lookup and staging value.

**Primary objective:** Give employees an efficient barcode-guided interface to the existing SAP operations, improving transaction speed and accuracy without replacing the ERP.

Supporting evidence: [RF status and measurement plan](../../evidence/rf-scanner-pilot.md).
