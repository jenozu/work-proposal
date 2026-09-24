---
type: idea
status: draft
created: 2026-09-24
updated: 2026-09-24
confidence: observed
tags:
  - finance
---

# Landed Cost Reconciliation

**Group:** Finance  
**Working stage:** existing tool requiring cloud-era SAP data workflow review. This is a proposal status, not a verification of the current code/deployment.

## Current inefficiency
Matching freight/brokerage charges to receipts and purchase orders takes repeated manual work.

## Proposed improvement
Import carrier invoice data and PO/GRPO exports, identify likely matches and prepare review-ready results.

## Testable measures
Minutes per carrier invoice; matching accuracy; missing-charge detection; corrections.

## External possibility
Specialized reconciliation package with onboarding or consulting.

## Boundaries and open questions
Direct SAP SQL is not assumed available. Use approved exports or supported integrations.

## Financial note
See [[Landed Costs - Working CBA]] for the project-specific financial evidence checklist. Before proceeding, identify workflow owner, frequency, existing cost, initial investment and operational dependencies.
