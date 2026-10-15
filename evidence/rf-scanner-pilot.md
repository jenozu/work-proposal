# RF Scanner / WMS — development and evaluation note

**Existing development:** An internal RF-scanner web application exists in the separate implementation repository [jenozu/rf-scanner](https://github.com/jenozu/rf-scanner). This proposal does not certify which modules are production-ready; verify against current code, a live demo and accepted tests.

## Initial operational scope

- Receiving and GRPO verification
- Sales order lookup and barcode-guided picking
- Inventory lookups / location information
- Staging and status tracking
- Controlled stock movement / exception verification

Potential adjacent capabilities (counting, carrier label processing, more advanced route optimization) are scoped under other proposal projects or later opportunities and should **not** be added into the RF Scanner benefit total again.

## Pilot observations to collect

Use real task distributions rather than a simple demonstration: 1–2 line orders, 3–5, 6–10 and higher-line-count orders where representative; mixed receiving documents; absent or mismatched barcode; serialized items; stock-location issues.

Record full **pick-to-stage elapsed time**, walking and sorting time, scanning and verification, corrections, SAP update/print steps, and employee satisfaction. For receiving, measure document search, item validation, quantities, GRPO confirmation and rework.

## Status and constraints

- **Functioning modules:** verify with application repository and operator acceptance; do not infer from filenames.
- **Integration:** require approved SAP method, least-privilege access, safe rollback and logs.
- **Benefit:** report only incremental time, error or throughput differences demonstrated by the pilot.
- **Costs:** account for scanner hardware, hosting, security, training, bug fixes, support and change management.

Older executive/detailed RF CBA drafts in [40-Ideas/rf-scanner](../40-Ideas/rf-scanner/) contain scenario assumptions; they are **not** verified results and are superseded for management by the current brief and measured trial data.
