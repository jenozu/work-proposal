# MARINDUSTRIAL Work Proposal — Master Plan

> Canonical task checklist for the Roadmap tool. The purpose is to **write, substantiate and present the operations improvement proposal and its individual cost-benefit analyses**, not to finish building every proposed application.
>
> Keep the short management documents easy to grasp (80/20); keep evidence, calculations and assumptions in detailed supporting documents. The **60-day pilot is a proposal to seek approval for**, not an already authorized project.
>
> Status convention: `[x]` means a document or structure is demonstrably present in this repository; it does **not** mean its content is approved, financially validated or that the software is operational. `[ ]` means substantive work, review or verification remains. Existing draft files should be improved in place, not duplicated.

## M1: Repository foundation and proposal scope

### Goal
Keep one navigable, auditable source of truth for the management proposal, the financial analyses, the pilot plan and the future commercial opportunity.

### Implementation
- [x] Establish the trade-brain-inspired numbered folder structure and `Home.md`, `README.md`, and `SCHEMA.md`.
- [x] Create `40-Ideas/` folders and overview notes for the currently identified tool opportunities.
- [x] Add shared executive/detailed CBA templates and the cost-benefit methodology.
- [x] Record the user-confirmed **60-day** pilot duration and the rule that internal and external value must be shown separately.
- [ ] Audit the ideas index against the current proposal and consolidate overlapping tools into a management-friendly shortlist.
  - Treat receiving/putaway, wave picking and cycle counting as RF Scanner modules unless separately justified.
  - Avoid presenting all 23 idea folders as commitments for the 60-day pilot.
  - Keep `40-Ideas/Ideas Index.md` aligned with the chosen grouping.
- [ ] Verify which existing tools are prototypes, in development, internally tested or operational.
  - Inspect the actual implementation repositories, screenshots and test evidence before making capability claims.
  - Update each idea's overview and `70-Project-State/Current Project State.md`.
- [ ] Review public-repository safety before adding supporting material.
  - Do not commit actual company invoices, customer lists, confidential prices, internal screenshots, credentials or unpublished quotations without authorization.
  - Store sensitive raw measurements in an approved private location; keep public documents anonymized.

## M2: Simple executive proposal

### Goal
Finish a clear 1–2-page management proposal that explains the opportunity, the plan and the requested approval without requiring technical knowledge.

### Implementation
- [x] Create the initial executive draft in `10-Strategy/Executive Proposal.md`.
- [ ] Refine the opening around repetitive work, operational inefficiencies, employee time and measurable results.
  - Use plain business language and the sequence **Identify → Measure → Develop → Test → Evaluate**.
  - Keep the proposal focused on outcomes rather than AI or technical implementation details.
- [ ] Confirm the short list of initial opportunities.
  - Introduce the RF Scanner, invoice comparator, invoice retrieval, shipping automation, commercial invoice generator and landed-cost processing.
  - Briefly mention future reporting, sales and customer-service opportunities without expanding the short proposal into a product catalogue.
- [ ] Finalize the internal-development advantage paragraph.
  - State that substantial work already exists on some tools, particularly the RF Scanner.
  - Present lower costs versus N'ware or external IT as a **potential advantage**, not a verified amount without equivalent quotations.
- [ ] Clearly explain the two separate business opportunities.
  - Internal: capacity released, process quality and potentially avoided operating costs.
  - External: *future* licensing, implementation and support revenue from tools first proven internally.
- [ ] Make the decision request explicit: approve a focused **60-day pilot** with agreed access, scope, success criteria and a day-60 report.
- [ ] Edit to fit 1–2 pages and review for clarity, unsupported promises and management-readability.
  - The executive proposal should be understandable without the detailed proposal or any slide deck.

## M3: Detailed management proposal

### Goal
Produce the extended supporting proposal explaining what will be investigated, how value will be demonstrated and how the initiative could evolve.

### Implementation
- [x] Create the initial extended draft in `10-Strategy/Detailed Proposal.md`.
- [ ] Expand the operational problem and opportunity using real, permission-safe examples from warehouse, purchasing, accounting and shipping workflows.
- [ ] Give each shortlisted tool a concise business description: current workflow, proposed change, stage, dependencies and expected measures.
  - Link to the corresponding `40-Ideas/<tool>/` overview instead of repeating lengthy technical specifications.
- [ ] Explain the proposed delivery method and safeguards.
  - SAP Business One remains the system of record; use approved exports/imports or supported integrations.
  - Include human review for sensitive transactions, permissions, testing, training and support.
- [ ] Explain the internal build-versus-buy comparison.
  - Account for remaining internal work, employee time, testing, licences, integration, maintenance, support and vendor alternatives.
  - Do not imply that the internal tool is already feature-equivalent to a vendor WMS.
- [ ] Explain commercialization as a separate long-term option.
  - Solve and validate an internal problem first, then research portability, customer demand, intellectual-property ownership, pricing, support and external implementation costs.
  - Keep speculative revenue out of internal payback calculations.
- [ ] Integrate the proposed 60-day pilot, deliverables, limitations and management decision points.
- [ ] Cross-check all claims against the short proposal and source notes; finalize the extended document for review.

## M4: Shared cost-benefit framework and portfolio summary

### Goal
Use one transparent method for all tools, with a one-page 80/20 summary per tool and an extended analysis supporting every significant figure.

### Implementation
- [x] Create `50-Cost-Benefit/Cost-Benefit Methodology.md`, `Templates/Executive CBA Template.md`, and `Templates/Detailed CBA Template.md`.
- [x] Create the initial `50-Cost-Benefit/Executive Portfolio Summary.md` comparison table.
- [ ] Confirm Finance-appropriate assumptions and definitions.
  - Verify loaded labour cost, annual working days, task frequency, usable-capacity factor, implementation labour, hosting and ongoing support.
  - Distinguish time released and usable operational capacity from actual cash savings or avoided spending.
- [ ] Standardize the **five-question executive CBA** for every shortlisted tool.
  - What problem exists? What changes? What annual internal value is expected? What does it cost and when could it pay back? Is there an external opportunity?
- [ ] Standardize the extended CBA evidence.
  - Baseline and after-process measurements; frequency and seasonality; errors and corrections; initial and recurring costs; assumptions; sensitivity; risk and confidence labels.
- [ ] Standardize the separate external commercial scenario.
  - State possible customer profile, price model, implementation revenue, recurring **gross** revenue, additional productization costs, support costs and evidence of demand.
  - Do not label hypothetical gross revenue as profit or a forecast.
- [ ] Establish a no-double-counting register before totaling the portfolio.
  - RF receiving, wave picking and inventory counting overlap with the main RF analysis.
  - Shipment notifications and the customer portal may reduce the same customer inquiries.
- [ ] Update the executive portfolio comparison only when each tool's inputs and confidence labels are documented.
  - Use **TBD/unknown** instead of invented financial amounts.

## M5: RF Scanner — first complete cost-benefit case study

### Goal
Make the RF Scanner the first complete example: a concise executive financial summary supported by a detailed, transparent analysis and a measurement plan.

### Implementation
- [x] Draft `40-Ideas/rf-scanner/RF Scanner - Overview.md`.
- [x] Draft `40-Ideas/rf-scanner/RF Scanner - Executive CBA.md`.
- [x] Draft `40-Ideas/rf-scanner/RF Scanner - Detailed CBA.md`.
- [x] Draft `40-Ideas/rf-scanner/RF Scanner - Pilot Test Plan.md`.
- [ ] Verify existing RF Scanner features and remaining work against the current implementation repository.
  - Separate functioning features from planned receiving, staging, wave picking, counting, shipping and integration capabilities.
- [ ] Replace illustrative baseline volumes with actual or explicitly sourced estimates.
  - Collect inventory lookup frequency and time; full picking time **including sorting**; receiving/putaway time; inventory-counting time; representative error/rework rates.
- [ ] Validate the cost assumptions.
  - The existing scenario uses 216 annual hours released, $30/hour, 75% usable capacity, $1,860 annual expenses and $3,560 remaining investment; **none are verified company results**.
  - Confirm remaining development time, training, equipment, hosting, support and implementation ramp-up.
- [ ] Recalculate internal value and payback with verified or clearly labelled estimated inputs.
  - Show actual avoidable cash expenses separately from usable employee-capacity value.
  - State sensitivity to volume, adoption, usable-capacity factor and recurring maintenance.
- [ ] If comparing internal development with N'ware/IT, obtain equivalent scoped quotes or explicitly leave the comparison qualitative.
- [ ] Assess the separate external opportunity without treating it as committed revenue.
  - The existing five-customer, $250/month plus $1,500 setup illustration is a **scenario only**; validate market demand, commercial build costs and support before promoting it.
- [ ] Bring the one-page RF CBA and detailed RF CBA into numerical and narrative agreement; mark every number measured, calculated, estimated, scenario or unknown.

## M6: Remaining shortlisted tool analyses

### Goal
Prepare comparable short and extended CBAs for the other initial tools, prioritizing writing and evidence collection rather than building all the software.

### Implementation
- [x] Create overview and working CBA notes for the identified tool portfolio in `40-Ideas/`.
- [ ] Complete the **invoice comparator** executive and detailed CBAs.
  - Measure document-checking frequency, manual review time, assisted review time, discrepancy accuracy, remaining build and support costs.
  - Files: `40-Ideas/invoice-comparator/`.
- [ ] Complete the **invoice retrieval** executive and detailed CBAs.
  - Measure requests, search time, match accuracy, permission constraints and maintenance.
  - Files: `40-Ideas/invoice-retrieval/`.
- [ ] Complete the **shipping automation** executive and detailed CBAs.
  - Measure end-to-end shipment processing time, data-entry errors, carrier costs where comparable, API permissions and ongoing maintenance.
  - Files: `40-Ideas/multi-carrier-shipping/`.
- [ ] Complete the **commercial invoice generator** executive and detailed CBAs.
  - Measure preparation time and correction rate; require human verification of tariff/origin data.
  - Files: `40-Ideas/commercial-invoices/`.
- [ ] Complete the **landed-cost processing** executive and detailed CBAs.
  - Measure invoice/receipt matching time and accuracy using the currently available SAP cloud data workflow.
  - Files: `40-Ideas/landed-costs/`.
- [ ] Review the remaining portfolio and identify which ideas merit a short preliminary CBA versus a later backlog entry.
  - Do not manufacture financial figures for concepts without a defined workflow, volume or implementation scope.
- [ ] Consolidate completed analyses into `50-Cost-Benefit/Executive Portfolio Summary.md`.
  - Show initial cost, recurring cost, annual internal value, payback, evidence quality and **separate** external potential.
  - Resolve overlapping savings before reporting any combined total.

## M7: Proposed 60-day pilot and measurement package

### Goal
Prepare a realistic pilot proposal that management can approve and that can replace planning estimates with actual results if authorized.

### Implementation
- [x] Draft `60-Pilot/60-Day Pilot Plan.md` with the agreed 60-day structure.
- [x] Draft `60-Pilot/Measurement Log Template.md`.
- [ ] Select a feasible set of pilot tools and agree on owners, access, test data and success criteria.
  - The RF Scanner is the initial case study; do not promise completion of all shortlisted tools within 60 days.
- [ ] Detail **Days 1–10**: workflow documentation, baseline volumes and representative timings.
- [ ] Detail **Days 11–30**: stabilize selected prototypes, check data integrity, test controls and train participants.
- [ ] Detail **Days 31–45**: representative before/after trials, error tracking and employee feedback.
- [ ] Detail **Days 46–60**: update CBAs, identify limitations and prepare management's decision package.
- [ ] Define evidence quality, sample sizes, exclusions, data storage, adoption ramp and the owner of each measurement.
- [ ] If management authorizes the pilot, run it and record outcomes without hiding neutral or negative results.
- [ ] Prepare a day-60 report with actual measurements, updated financial analyses, remaining investment and next-stage options.

## M8: Commercialization and external-value assessment

### Goal
Explain the possible longer-term product business clearly while keeping it separate from the internal operational case.

### Implementation
- [x] Draft `10-Strategy/Commercialization Strategy.md`.
- [ ] Identify which internal tools are realistically reusable versus better suited to one-time custom implementations.
- [ ] Describe possible licence, setup, support and custom-development models without presenting untested prices as market facts.
- [ ] Outline what productizing the RF Scanner would require beyond the internal version.
  - Configuration, tenant security, integrations, onboarding, documentation, hosting, monitoring and customer support.
- [ ] Research potential customer demand and obtain initial pricing/implementation feedback if permitted.
- [ ] Confirm employer intellectual-property ownership, distribution rights, customer data handling and vendor/API licensing requirements before any external offering.
- [ ] Prepare a distinct external revenue **scenario and cost model** for each credible candidate.
  - Separate gross subscription revenue, one-time fees, recurring service costs and additional commercialization investment.
- [ ] Summarize commercial potential in the detailed proposal without using hypothetical sales to justify the 60-day pilot.

## M9: Final management package and presentation

### Goal
Deliver an easy-to-read decision package with deeper documentation available on request.

### Implementation
- [ ] Finalize the **1–2-page executive proposal**.
- [ ] Finalize the **4–6-page detailed proposal** and ensure it matches the executive version.
- [ ] Finalize the **one-page portfolio financial comparison** with appropriate TBD labels and evidence confidence.
- [ ] Finalize **one-page CBAs** for the shortlisted tools and link their detailed supporting analyses.
- [ ] Finalize the **60-day pilot approval request**, measurement plan and proposed day-60 deliverables.
- [ ] Check all figures, source references, overlapping benefits, cost comparisons and commercial claims for consistency.
- [ ] Perform a plain-language review: can management understand the problem, solution, investment and expected evidence in approximately two minutes?
- [ ] Prepare optional presenter slides from the finalized written documents.
  - Slide design and infographics are **supporting materials**, not prerequisites for completing the proposal; an infographic is optional.
- [ ] Assemble a final management handoff package and record feedback, decisions and revisions in `30-Decisions/Decision Log.md`.

## Completion standard

The **proposal-writing project** is complete when the executive proposal, extended proposal, shortlisted one-page CBAs, detailed supporting CBAs, consolidated comparison and 60-day pilot request are consistent, evidence-labelled and ready for management review. **Actual execution of the pilot and future software commercialization are conditional follow-on work**, not prerequisites for presenting the proposal.
