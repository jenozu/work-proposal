# Cycle Counting — Inventory Data (Restricted)

This folder documents the expected source files for the inventory cycle-counting analysis. **Do not commit internal SAP exports or other confidential operational workbooks to this public repository.**

## Planned source files

- `05_Inventory_Movements_60M.xlsx`
- `06_Sales_Delivery_60M.xlsx`
- `07_Purchasing_Receiving_60M.xlsx`
- `08_Bin_Locations_Inventory.xlsx`
- `09_Historical_Inventory_Counts_60M.xlsx`
- `master_inventory.xlsx`

The six workbooks are currently **not stored in GitHub**. Their filenames are recorded here for organizing the project; this file does not imply the data has been published or reviewed.

## Handling and provenance

- Retain the original Excel files in `.xlsx` format, unchanged.
- The filenames above remove temporary upload suffixes like `(3)` and `(4)`.
- Store the originals only in a Marindustrial-approved **private** repository or document location with appropriate access controls.
- Do not put stock quantities, item-level valuations, customer/vendor records, serial numbers, or transaction-level details into this public repository.
- The local `.gitignore` in this folder reduces accidental Git commits; it does **not** block GitHub browser uploads or forced commits.
- A cycle-counting analysis may reference the filenames while keeping real source contents offline.
