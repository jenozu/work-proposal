# Project 3 — Automated Batch Shipping & SAP Integration

## Current Challenge

The existing workflow requires entering Purolator shipment details and printing a label, then locating the related order in SAP Business One, creating a delivery and printing its paperwork. Repeating the two-system sequence adds administrative work to each outgoing order. Prior handling measurements were approximately **30 seconds for Purolator** and **45 seconds for SAP**, or **75 seconds per shipment**.

## Proposed Solution

Build a controlled interface to enter or retrieve the sales-order number, package weight, dimensions and relevant carrier selections; then use approved integrations to prepare the Purolator label and corresponding SAP delivery. Batch processing may assist eligible orders, but serial numbers, mismatched lines, unusual shipments, voided labels and unsuccessful requests must prompt review. No uncontrolled SAP posting or assumed access is proposed.

## Preliminary Analysis

An additional historical review counted **2,020 completed shipments from October 2025 through September 2026**, excluding cancellations. The **proposed**, unverified assisted-handling target is **10–15 seconds** for an eligible shipment. Against 75 seconds, that implies **60–65 seconds potentially released per shipment**, a **80.0–86.7%** reduction. If every historical shipment were eligible and reached the target, the annual opportunity would be **33.7–36.5 employee-hours**. This is a **projection from measured and historical inputs**, not a realized trial result; some orders may not be suitable for automation.

## Expected Benefits

The direct dollar value of those hours might be relatively modest. The project remains useful as a clear demonstration of efficient workflow integration and a way to preserve shipping capacity during peak periods. Faster processing, fewer duplicate entries and greater consistency may have practical value, but time released does not imply fewer paid hours.

## Pilot & Evaluation

Time complete comparable manual and assisted shipments, including lookup, printing, SAP delivery, carrier acceptance, error recovery, retry/void cases and review. Verify order details, quantities, serials, labels, tracking and reconciliation. Establish actual eligible annual volume, operator time versus system wait time, integration costs, maintenance and exception rate.

## Primary Objective

Reduce repetitive shipping administration while keeping Purolator and SAP delivery processing accurate, supported and auditable.

Supporting evidence: [shipping calculations](../../evidence/shipping-baseline.md).
