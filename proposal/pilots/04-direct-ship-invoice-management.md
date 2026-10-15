# Project 4 — Automated Direct-Ship Processing & SAP Invoice Management

## Current Challenge

This project covers **two related but distinct SAP administrative workflows**.

**Interbranch direct shipping:** A customer purchases through Mississauga, but another Marindustrial branch ships directly to that customer and invoices the Mississauga branch. The local administrative process can require reviewing the branch invoice and corresponding order, confirming delivered items, quantities, serial numbers and charges, and completing the appropriate SAP receiving, purchasing and customer-invoicing steps. Multiple documents and record checks slow completion.

**Supplier invoice PDF management:** Employees may also need to locate the correct vendor invoice, match it to the appropriate SAP transaction or purchasing record, and upload or attach the PDF manually. Finding the correct document, selecting the matching record and checking the attachment are separate repetitive activities.

## Proposed Solution

Create a common guided interface to identify eligible direct-ship transactions, retrieve matching sales and purchasing documents, flag missing or mismatched data, and prepare authorized SAP actions for review. In a complementary workflow, retrieve permitted invoice PDFs from approved folders or email sources, match invoices using appropriate identifiers, and attach them to the correct SAP records with confirmation and exception reporting.

System changes should use **approved SAP Business One integration methods**; sensitive inventory, accounting and invoicing actions require explicit validation, audit trails and authorized approval. The tool should not assume that all branch transactions follow identical rules.

## Preliminary Evidence & Expected Benefits

Early document-retrieval analysis identified repeated vendor documents and duplicate handling opportunities, but these observations **do not establish the time saved in SAP direct-ship processing or invoice attachment**. Separate before/after timings and annual transaction counts are required for a credible financial estimate.

Potential benefits include fewer manual entries and searches, faster completion of interbranch administration, more consistent invoice-to-record matching, improved traceability and more timely customer invoicing.

## Pilot & Evaluation

Compare representative direct-ship transactions and invoice attachments under the existing and assisted processes. Time each sub-workflow separately; record manual steps, match accuracy, missing serial numbers, adjustments, error and exception handling, and review time. Management and Accounting must validate the SAP document flow before posting transactions in production.

**Primary objective:** Reduce repetitive SAP administration while accelerating accurate direct-ship processing and preparation for customer invoicing.

Supporting evidence: [Invoice research and open measurements](../../evidence/invoice-and-direct-ship.md).
