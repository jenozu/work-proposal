# Automated inventory cycle counting — research notes

## Recorded preliminary findings

- Historical full count requires approximately **4 employees × 2–3 days**. Assuming **8 hours/day**, that is **64–96 direct employee-hours** per count. This excludes broader operational disruption and preparation/cleanup.
- Reported **count-line accuracy**: **2023: 97.36%**, **2024: 94.72%**, **2025: 91.41%**. Verify extraction definitions, item scope, locations and whether percentages are directly comparable across years.
- SAP preliminary scope: **3,833 stocked item records** identified. An earlier working classification showed **A: 87**, **B: 304**, **C: 2,358**, which **does not total the full 3,833**. These provisional segments are not a final assignment and must not be presented as full coverage.
- Preliminary plan: **15–20 minutes of physical counting per workday**, depending on item mix, movement, count frequency, layout and interruptions. Earlier scenario about **19.5 minutes/day** included a small handling allowance but did not validate discrepancy investigation or reporting overhead.

## Model under consideration

Rather than unit price alone, consider (a) stock value or exposure, (b) movement/sales activity, (c) discrepancy history and (d) operational criticality or lead time. High-sales-value items may deserve attention even at moderate unit price, and expensive slow-moving items may require different frequency rules. Confirm actual annual sales, stocked value, movements, adjustment history and location data through an approved SAP extract.

A/B/C count intervals are **parameters to test**, not a settled company policy. Do not use fixed count quotas unless the data confirms staff can complete them without obstructing operations.

## What must be validated

- Frequency and duration of full count, audit/Finance constraints and required year-end controls.
- True cycle count task time **including** travel, access, frozen-bin controls, verification, investigations and adjustments.
- Item/location coverage and annual labor at realistic frequencies.
- Impact on shipment/receiving activities during a controlled count.
- Accuracy metrics defined consistently over time; approved threshold for replacing or shortening the annual shutdown.

## Cost-benefit caution

**15–20 min × 250 workdays = 62.5–83.3 hours/year of physical counts alone.** Against 64–96 hours of direct year-end counting, that does **not** show robust payroll savings; actual investigations may increase total labour. Operational continuity and accuracy are stronger initial objectives.

Source: October 2026 SAP analysis and warehouse workflow conversations; raw records not committed.
