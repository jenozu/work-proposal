---
type: idea
status: draft
created: 2026-09-24
updated: 2026-09-24
confidence: observed
tags:
  - shipping
---

# Shipping Automation and Carrier Comparison

**Group:** Shipping  
**Working stage:** Purolator batch-shipping prototype exists; multi-carrier expansion proposed. This is a proposal status, not a verification of the current code/deployment.

## Current inefficiency
Repeated shipment data entry, rate checking, label creation and recordkeeping.

## Proposed improvement
Retrieve order details, validate addresses, compare carrier services where authorized, create labels and save shipment history.

## Testable measures
Minutes per shipment; rekeying errors; eligible carrier-cost differences; shipment exceptions.

## External possibility
Managed shipping tool priced by customer/location/usage or custom deployment.

## Boundaries and open questions
Carrier APIs, contracts and rating permissions must be checked before multi-carrier claims.

## Financial note
See [[Shipping Automation - Working CBA]] for the project-specific financial evidence checklist. Before proceeding, identify workflow owner, frequency, existing cost, initial investment and operational dependencies.
