# Project 3 — Automated Batch Shipping & SAP Integration

## Current Challenge

When a customer order is ready to ship, the employee currently performs two separate administrative tasks: creating the **Purolator shipment and printing a label**, then locating the corresponding **SAP Business One sales order, creating a delivery note and printing it**. This means navigating between systems and repeatedly handling transaction details.

Workflow timing indicates approximately **30 seconds for Purolator** and **45 seconds for SAP**, or **75 seconds of combined administrative processing per shipment**. Some busy days exceed **15 shipments**, but this peak is **not** used as a daily annual average.

## Proposed Solution

Build a controlled shipping interface in which the employee supplies the **sales order number**, confirms required shipment information, and enters **package weight, dimensions and shipment type where applicable**. The tool would retrieve permitted order details, prepare the carrier shipment and label, and generate and print the appropriate SAP delivery document through an approved integration. Exceptions, serial-number requirements and failed/partial transactions would require validation rather than silent automatic posting.

The initial processing target is **10–15 seconds per normal shipment**, subject to a real end-to-end pilot. Where practical, enable processing multiple ready orders in a queue, without bypassing shipment-specific checks.

## Expected Benefits

Under target assumptions, direct administrative handling could decrease by **60–65 seconds per shipment**, approximately **80–87%**. At an illustrative **5–10 shipments on each of 250 workdays**, this equates to **approximately 21–45 hours per year** of employee capacity. At **1,000 shipments**, the same estimate is **16.7–18.1 hours**. Neither estimate represents a confirmed annual volume or realized payroll reduction.

The operational benefit may be especially valuable during peak periods, when reducing repetitive administration helps maintain shipping throughput.

## Pilot & Evaluation

Measure current and automated handling using comparable orders, including data lookup, label generation, SAP creation, printing, failed API calls, corrections, shipment voiding and verification. Confirm permissions and supported methods for Purolator and SAP integration. Keep order accuracy and accountability at least as strong as the existing process.

**Primary objective:** Reduce shipping administration and improve throughput by combining two linked operations into one guided workflow.

Supporting evidence: [Shipping time study and formulas](../../evidence/shipping-baseline.md).
