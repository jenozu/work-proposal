# Near-Term Backlog — Automated Direct-Ship Processing & SAP Invoice Management

**Status:** moved from the fifth-pilot package to **Tier 1 / near-term Future Opportunities** on October 16, 2026. Reportedly **partially built**; actual implementation status requires code inspection. This is **not Project 4** in the current management proposal.

## Challenge

Two related yet independently measurable workflows require repeated SAP and document handling. In **interbranch direct shipping**, another branch fulfils a Mississauga customer order and invoices Mississauga; the local process must validate items, quantities, serials, orders and charges before appropriate purchasing/receiving and customer-invoice actions. In **supplier invoice PDF handling**, employees retrieve the right document, match its identifiers and attach or file it to a relevant SAP record.

## Proposed direction

Guide operators through document lookup and matching; show missing or conflicting data; prepare only permitted SAP actions for review; and keep audit and exception logs. Require Purchasing, Accounting and IT confirmation before modifying live SAP financial records. The partially developed foundation may offer a head start but must not be called production ready without verification.

## Evidence and pilot measurements

Separately time direct-ship processing and invoice attachment, including exceptions and annual volumes. An adjacent 12-month document retrieval study observed **1,074 unique invoice candidates**, **86 duplicates** and around **30 seconds per manual file save**, but these do **not** establish direct-ship SAP transaction savings.

Further detail: [direct-ship/invoice research](../../evidence/invoice-and-direct-ship.md).
