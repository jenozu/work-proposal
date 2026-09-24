---
type: architecture
status: draft
created: 2026-09-24
updated: 2026-09-24
confidence: observed
tags:
  - integration
  - security
---

# Delivery and Integration Model

## Internal delivery
Prefer small workflow-specific tools that complement existing business systems. Capture the source system, data refresh schedule, required permissions, exception path, auditability and rollback before pilot use.

## ERP boundary
SAP Business One remains authoritative for operational transactions. Current cloud-era SQL access cannot be assumed. Explore approved reports/files and supported APIs only after confirming technical and commercial availability.

## External product architecture
A commercial product may require tenant isolation, configurable warehouses/workflows, authentication, data import/export, onboarding, audit logs, backups, monitoring, licensing and support. These costs are separate from finishing the internal prototype.

## Controls
Protect customer/vendor and inventory data, require review for sensitive changes, document failures and recoveries, and avoid committing live business data to this public repository.
