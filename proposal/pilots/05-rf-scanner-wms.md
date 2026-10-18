# Project 5 — RF Scanner & Warehouse Management System

## Current Challenge

Warehouse receiving, picking and staging may involve repeated SAP screen navigation, order searches, location lookup and entry verification. These small tasks add friction during high-volume periods.

## Proposed Solution

Expand the **existing internally developed RF Scanner web application** into a controlled, mobile-friendly barcode interface for GRPO receiving, sales-order picking, item and bin lookup, staging/status and approved movement verification. SAP Business One remains the system of record.

## Preliminary Analysis

The implementation codebase exists at [jenozu/rf-scanner](https://github.com/jenozu/rf-scanner). Exact deployed modules, integration behaviour and readiness require code review and hands-on verification; an existing prototype is not proof of an end-to-end live workflow. Representative order sizes and receiving exceptions must be sampled.

## Expected Benefits

Possibly faster transaction lookup and confirmation, reduced keying errors and more dependable tracking of staged orders. These potential improvements should not be equated with automatic staffing reductions.

## Pilot & Evaluation

Compare complete manual and assisted receiving, lookup, picking and staging tasks—including scanning errors, serials, exceptions, correction, device costs and support. **Avoid double counting:** count verification belongs to Project 1, carrier/SAP shipping to Project 3, and location/walking improvements from stock relocation to Project 4.

## Primary Objective

Deliver a practical warehouse mobile interface that improves SAP transaction correctness and employee productivity while preserving authorized controls.

Supporting evidence: [RF Scanner evaluation](../../evidence/rf-scanner-pilot.md).
