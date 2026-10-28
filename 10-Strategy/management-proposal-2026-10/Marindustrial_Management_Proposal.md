# Make everyday operations simpler.
*A practical, low-risk proposal for an internal software and business systems capability at Marindustrial Inc.*

## The opportunity
Across shipping, inventory, reporting and warehouse work, employees repeatedly gather information, enter data, look for items and correct preventable errors. Targeted software can simplify these tasks while SAP Business One remains Marindustrial's core business system.

Several tools are already well advanced. What is missing is not ideas but protected time and clear ownership to finish, test, deploy and maintain them.

## What Marindustrial stands to gain
- **More time for useful work.** Reduce repetitive handling and unnecessary warehouse movement.
- **More reliable operations.** Standardize repeat tasks, validate entries and make issues easier to trace.
- **Better management visibility.** Make recurring reports clearer, more consistent and easier to act on.
- **A possible long-term product opportunity.** Tools proven inside Marindustrial might later be adapted for other distributors and warehouses. This is separate from the internal case, is not counted in any benefit, and would first need agreement on ownership and rights (see the appendix).

## Five pilot projects
1. **Automated Inventory Cycle Counting** — Earlier discrepancy detection
2. **Centralized Reporting & Automated BI** — Faster, consistent reporting
3. **Automated Batch Shipping & SAP Integration** — Less repeated shipment entry
4. **Warehouse Slotting & Picking Optimization** — Shorter picking routes
5. **RF Scanner & Warehouse Management System** — More traceable warehouse work

> **THE DECISION REQUESTED:** Authorize a controlled 60-day evaluation of one or two pilots, starting with Automated Batch Shipping. The evaluation produces measured results that management can use to decide whether an internal software developer / business systems role is justified. It is not a request for five deployments or for a permanent position today.

[[PAGE_BREAK]]

# Where software can remove routine friction
*Pilots 01 to 03. These are opportunities to be measured, not promised savings.*

## 01 | Automated Inventory Cycle Counting
**The issue:** Year-end counting concentrates staff time and may delay discovery of stock discrepancies.

**The approach:** Test short, planned ABC counts using provisional 30/90/180-day review cycles, with documented variance checks. These intervals are test hypotheses, not an approved inventory policy.

**Expected benefit:** Less concentrated disruption, earlier error detection and clearer inventory records.

**Pilot measure:** Counting hours, discrepancy rates and total work compared with the current process.

## 02 | Centralized Reporting & Automated BI
**The issue:** Employees spend time preparing similar reports, often with inconsistent definitions.

**The approach:** Automate one recurring report or small dashboard from approved SAP data, with agreed KPIs. A prototype dashboard concept exists and has been demonstrated only with hypothetical sample data.

**Expected benefit:** Less manual preparation, more consistent reporting and quicker visibility into exceptions and into which products drive revenue and gross profit.

**Pilot measure:** Preparation time, data accuracy and usefulness to managers.

## 03 | Automated Batch Shipping & SAP Integration
**The issue:** Each shipment is currently entered in the carrier system and again in SAP. Timed by the proposer, this takes about 30 seconds in Purolator plus about 45 seconds in SAP, or roughly 75 seconds per shipment.

**The approach:** A single entry screen for the sales order number, weight, dimensions and prepaid or collect, then one submit-and-print step for a whole batch. It is near complete as a standalone Purolator tool. Connecting it to SAP, so delivery documents print in the same step, is the next stage and is not yet built.

**Expected benefit:** The design target is roughly 10 to 15 seconds per shipment. This is a design estimate that the pilot will time, not a measured result.

**Pilot measure:** Time per shipment before and after, errors, exceptions and duplicate prevention.

[[PAGE_BREAK]]

# Make the warehouse easier to run
*Pilots 04 and 05. Better item placement and practical scanning can complement one another.*

## 04 | Warehouse Slotting & Picking Optimization
**The issue:** Frequently picked parts can be far from the shipping area, increasing walking time.

**The approach:** Rank items by how often they are physically picked, map travel routes and test a limited, reversible relocation of suitable items.

**Expected benefit:** Less unnecessary travel, more efficient picking and a more practical layout.

**Pilot measure:** Actual walking distance, picking time and accuracy before and after the pilot.

## 05 | RF Scanner & Warehouse Management System
**The issue:** Manual lookups and inconsistent handling can slow receiving, picking and counting.

**The approach:** Test the existing scanner application for guided warehouse tasks and verified item and bin records before any SAP posting. Over time, the shipping tool would join it: once orders are scanned, their weights and dimensions could flow straight into shipment processing.

**Expected benefit:** More consistent processes, improved traceability and fewer manual mistakes.

**Pilot measure:** Transaction time, scanning accuracy, corrections and staff usability.

## Simple example: slotting by pick frequency
**PACK / SHIP** (dispatch starting point) → **HIGH PICK** (closest suitable bins) → **MEDIUM PICK** (next suitable bins) → **LOW PICK** (further suitable bins).

Placement also depends on size, weight, safe handling and storage requirements. Physical pick frequency, not sales value, drives the initial ranking.

> **WHY THESE PROJECTS WORK TOGETHER:** Inventory accuracy, efficient picking, scanning and shipping support the same warehouse outcome. Any shared time savings is counted only once.

[[PAGE_BREAK]]

# Where each pilot stands today
*Progress figures are the proposer's own estimates of build completion. They are not production or financial results.*

## 01 | Automated Inventory Cycle Counting
**Stage and progress:** Early build, about 50% by the proposer's estimate.

**Evidence:** Counting method and provisional intervals defined. No baseline counting times yet; SAP source data still to be gathered.

## 02 | Centralized Reporting & Automated BI
**Stage and progress:** Prototype and detailed build plan, about 65%.

**Evidence:** Dashboard concept demonstrated with hypothetical data only. No real KPIs or data access agreed yet.

## 03 | Automated Batch Shipping & SAP Integration
**Stage and progress:** Near-complete standalone Purolator tool, about 80%. SAP connection not yet built.

**Evidence:** Timed baseline of about 30 seconds in Purolator plus 45 in SAP. About 3,000 shipment documents a year in an SAP query (filters to be confirmed).

## 04 | Warehouse Slotting & Picking Optimization
**Stage and progress:** Method defined, about 50%.

**Evidence:** Approach set out (physical pick frequency, route mapping, reversible moves). No measurements or relocations yet.

## 05 | RF Scanner & Warehouse Management System
**Stage and progress:** Working development project, about 70%.

**Evidence:** Which features are live must be confirmed against the implementation repository. Testing can use the existing SAP test server; any licence for posting into SAP is still to be confirmed.

[[PAGE_BREAK]]

# The proposed role: internal software and business systems
*An accountable owner for building, testing, deploying and maintaining operational tools.*

## What the role is
A software developer / business systems role inside Marindustrial that finds repeated operational problems and builds, tests, deploys, maintains and improves internal tools, including tools connected to SAP Business One. It is not a generic SAP consultant and not IT support.

## What the role does
- **Identify.** Observe workflows, measure the current process and agree what is worth fixing.
- **Build and test.** Develop small tools with version control, test data and a manual fallback.
- **Deploy and train.** Release safely, document the tool and train its users.
- **Maintain and improve.** Fix defects, support users and keep tools working as processes change.
- **Report.** Track time released, errors and adoption so value is visible.

## What the role does not do
- It does not replace IT or the SAP partner. Integrations use approved access, with IT and SAP participation.
- It does not post to SAP without testing and acceptance.
- It does not promise payroll savings. Released time is operating capacity unless a real expense is avoided.

## Why a role rather than a one-off project
A tool is only useful while someone keeps it working. Testing, security, training, documentation, user support and maintenance are continuing work, and a backlog of further improvements already exists. A named owner turns one-off tools into a managed set of supported systems.

> **HOW A PERMANENT ROLE WOULD BE DECIDED:** At the day-60 review, management considers the measured results, the support effort the tools need and the work still waiting. Role scope and compensation would then be discussed as a separate, later decision.

[[PAGE_BREAK]]

# Why evaluate an internal developer?
*The benefit is ongoing ownership of operational improvements, not simply five separate tools.*

## Three reasonable options

### Continue manually
**Where it works well:** No new software commitment; simple processes may not need automation.

**Main trade-off:** Recurring staff effort and inconsistencies remain.

### Buy or outsource
**Where it works well:** Suitable for established products, specialist integrations and complex needs.

**Main trade-off:** Licence, customization, support and vendor coordination costs. No like-for-like quotes have been obtained yet.

### Develop internally
**Where it works well:** Useful for Marindustrial-specific repeat workflows needing ongoing adaptation, and where substantial work already exists.

**Main trade-off:** Requires protected development time, safe system access and continuing support.

## What the proposer offers
- **The first approved project at no charge.** If management agrees to implement a project, the proposer will deliver the first one without charge for development time.
- **Personal time.** About two hours of after-hours time toward the evaluation, with the schedule to be agreed.
- **Fair terms afterwards.** If management then wants more work, a payment structure for additional time can be agreed once the first results have been reviewed.

## Why the starting cost is low
Marindustrial already has an SAP test server, so features can be tested without a new environment or purchase. With a read-only SQL username and password, approved by IT, the proposer could extract SAP data automatically for testing and reporting at no additional software cost expected. Writing back into SAP is a separate later step that would need IT and SAP agreement and may need a licence.

## Investment discipline
Build when the problem is specific and repeated. Buy when an existing product fits. Stop when measured benefits do not justify the cost.

[[PAGE_BREAK]]

# A defined 60-day test. A clear decision.
*Management retains control over pilot selection, access, time allocation and whether work continues.*

## How the evaluation would work
- **Days 01 to 15 | Choose and measure:** Confirm the sponsor, the pilot (starting with Batch Shipping) and baseline times.
- **Days 16 to 30 | Build and test:** Finish the minimum solution and validate data safely.
- **Days 31 to 45 | Trial at work:** Compare real before-and-after outcomes, including errors.
- **Days 46 to 60 | Review and decide:** Assess benefits, cost, ongoing support and next steps.

## What counts as success
Time per task, error and rework rates, usability, adoption and ongoing maintenance effort. For shipping, the test is whether the new process beats the timed 75-second baseline in real use. Recovered time is operating capacity, not automatic payroll savings.

## Resources and approvals requested
1. Authorize the 60-day evaluation and agree a limited work-time allocation (to be agreed) in addition to the proposer's own time.
2. Select one or two pilots and name a management sponsor.
3. Permit use of the existing SAP test server and read-only SQL access to SAP data, and staff participation, subject to IT and SAP policies.
4. Schedule a day-60 review before approving further investment or a permanent role.

## Main risks and how they are controlled
- **SAP access or licence is delayed.** Shipping runs as a standalone tool first, so value does not depend on SAP access.
- **Data access risk.** Access is read-only and tested on the SAP test server first. Nothing is written to production SAP without IT and SAP acceptance.
- **A tool gives wrong results.** Parallel manual checks, duplicate prevention and a manual fallback during the trial.
- **Time runs short.** Scope is limited to one or two pilots, and a neutral or negative result is reported as such.
- **One person owns everything.** Documentation and version control from the start, with a continuity plan.

> **DAY-60 DECISION:** Approve additional development only if the evaluation shows a credible operational benefit, acceptable system risk and enough recurring work to support ongoing ownership. No permanent staffing decision is required now.

[[PAGE_BREAK]]

# Appendix: future opportunities
*A backlog for later consideration. None of these is part of the 60-day request.*

## Near-term opportunities (review after the first pilot results)
- **Direct-Ship Processing & SAP Invoice Management.** Reduce repeat handling of direct-ship transactions, invoice searches and document filing. First in line; scope and permissions still to be confirmed.
- **Invoice Retrieval.** Search approved mailboxes and folders for supplier invoices. Earlier prototype; current status to be verified.
- **Invoice / PO / GRPO Comparator.** Flag differences between purchase orders, receipts and invoices. Previously developed; deployment to be verified.
- **Landed Cost Reconciliation.** Match freight and brokerage charges to receipts. Existing tool; needs review against current SAP data access.
- **Commercial Invoice Generator.** Prepare international shipping documents from a few inputs, with human review of customs details.
- **Shipment Notifications.** Send confirmations and tracking automatically to reduce manual emails.

## Later opportunities (concept stage)
- Customer order-status portal and customer service assistant
- Inventory and purchasing analytics, dormant-customer identification and product cross-sell analysis (extensions of the reporting pilot)
- SAP operations companion, GRPO document attachment and SAP document auto-print
- Teams operations task dashboard and internal information search
- Website and lead-capture improvements and market and competitor monitoring

Receiving, putaway and wave picking are treated as modules of the RF Scanner project, not separate projects.

## Long-term commercialization (separate from the internal case)
If a tool proves valuable inside Marindustrial, it could later be offered to other distributors or warehouses through licensing, setup and support. This would require, first: agreement on who owns the software and the right to sell it; evidence of customer demand and willingness to pay; carrier and SAP licensing terms; and the added cost of support and security. No revenue is assumed anywhere in this proposal.

---

**Status:** Management review draft, October 2026. Times described as targets or estimates are not verified production improvements. Progress figures are the proposer's estimates.
