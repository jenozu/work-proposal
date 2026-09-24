---
type: idea
status: draft
created: 2026-09-24
updated: 2026-09-24
confidence: observed
tags:
  - warehouse
---

# Wave Picking Optimization

**Group:** Warehouse  
**Working stage:** planned/partly developed within RF initiative; confirm live behavior. This is a proposal status, not a verification of the current code/deployment.

## Current inefficiency
Picking orders separately can create repeat trips through the same warehouse aisles.

## Proposed improvement
Batch compatible orders into organized picking routes and track final sorting and order completion.

## Testable measures
Total elapsed picking plus sorting time; steps; repeated stops; picks per hour; mis-picks.

## External possibility
RF Scanner feature, or eventually a compatible picking add-on.

## Boundaries and open questions
Compare matched 3-, 5-, and 10-order samples. Do not count separately if included in RF Scanner benefits.

## Financial note
See [[Wave Picking Optimization - Working CBA]] for the project-specific financial evidence checklist. Before proceeding, identify workflow owner, frequency, existing cost, initial investment and operational dependencies.
