# Proposal Note Schema

Modeled on `jenozu/trade-brain`: numbered folders, Obsidian-compatible Markdown, durable decisions, and linked notes.

## Frontmatter example
```yaml
---
type: idea
status: draft
created: 2026-09-24
updated: 2026-09-24
confidence: hypothesis
tags:
  - warehouse
---
```

Types: `strategy`, `proposal`, `architecture`, `decision`, `idea`, `cost-benefit`, `pilot`, `project-state`, `glossary`, `source`, `template`.

Status: `draft`, `active`, `measured`, `approved`, `deprecated`, `superseded`.
Confidence: `hypothesis`, `estimated`, `observed`, `tested`, `validated`.

Each tool folder owns its overview and CBA. Shared financial assumptions live in `50-Cost-Benefit/`. Every financial claim must identify its data source, time period, scope, and whether it is an estimate, measurement or commercial scenario. Avoid double-counting related modules.

This repository is a proposal/knowledge vault, **not** the source of truth for implemented software. Check code/tests in the linked project repos, and approved SAP vendor documentation for integration claims.

**Public-repository rule:** Do not commit employer-confidential information, real invoices, customer lists, inventory values, employee details, credentials, internal screenshots, or unpublished vendor quotations without explicit approval. Keep private working data elsewhere. Use synthetic examples here.
