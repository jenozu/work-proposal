# Research Brief — AI Agents and Orchestration

**Status:** implementation research for NotebookLM and Codex; **not** an approved architecture, new priority pilot or autonomous SAP permission.

## Objective

Explore whether narrowly scoped AI workers could help design, test, diagnose or explain Marindustrial's proposed tools while ordinary deterministic software remains responsible for measurements, routing, financial calculations, permission checks and ERP transactions.

## Ground rules

- Prefer **standard code** for route optimization, ABC scheduling, joining records, quantitative analysis, label creation and document reconciliation.
- Consider language-model assistance only for ambiguous, text-heavy tasks such as interpreting authorized SOPs, triaging report anomalies or suggesting likely invoice matches with source references.
- Separate agents by function and **least privilege**. Use input/output schemas, provenance, logs, budgets, bounded retries, timeouts, evaluation datasets and failure escalation.
- Implement **human approval** before SAP inventory, receiving, invoice, purchasing or delivery changes, carrier bookings, customer messaging, and any physical slotting relocation.
- No unsupervised access to confidential customer/inventory data. Use synthetic or explicitly approved data in initial experiments.

## Candidate phased experiments

| Phase | Possible agent/worker | Why investigate | Boundary |
|---|---|---|---|
| 0 | Requirements and SOP drafting assistant | Convert approved process notes into testable workflow descriptions | No production integrations |
| 1 | Read-only reporting exception analyst | Explain mismatches after deterministic validation | Cite source fields; no SAP writes |
| 1 | Internal documentation retrieval | Answer warehouse process questions from approved references | Sources and permission checks |
| 2 | Invoice-matching reviewer assistant | Suggest matches and flag uncertain IDs or missing serials | Human confirmation; no automatic posting |
| 2 | Pilot research orchestrator | Coordinate data checks, simulations, report drafts and QA tasks | Approved/synthetic datasets; independent validation |
| 3 | Transaction-assist workflows | Consider only after repeatable correctness and security testing | Separate employer/IT and integration approval |

## Illustrative control flow

**Request → schema validation → deterministic source query or calculation → optional AI interpretation → rule/policy verification → human approval if action → controlled executor → reconciliation and audit → review of outcomes.**

A coordinator may schedule independent bounded workers, but must track task state, costs and errors. Agent confidence cannot substitute for comparing results with SAP/warehouse records. A failed validation stops or escalates; it does not silently proceed.

## Research questions for NotebookLM

1. Which of the five current pilots contain work that actually requires an AI agent rather than conventional programming?
2. How should free/open-source orchestration options compare on licensing, reliability, local Windows development, Linux hosting and integration complexity?
3. Which agents should have **read-only** tools, and what should the approval workflow for proposed actions look like?
4. How can tasks be idempotent, observable, permissioned and recoverable after failures?
5. What evaluation set demonstrates lower net review effort, good accuracy and manageable latency/cost?
6. What shared adapters, schema contracts and testing patterns could be used across independently maintained app repositories?

## Deliverables after research, not now

A documented technology decision, a permission matrix, a synthetic read-only proof of concept with automated tests, error logs and performance measurements, and an explicit decision on whether any AI approach improves on simpler deterministic automation.

**Presentation boundary:** keep the management pre-proposal focused on measured operational outcomes and internal development capability. Agent orchestration is only one potential implementation method.
