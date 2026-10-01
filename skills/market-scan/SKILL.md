---
name: market-scan
description: Screen every business of one type around a U.S. place with a Groundwork market report, to find independent shops to approach about buying or the spots with the most spending per competitor. Use when someone wants acquisition targets, a shortlist of businesses, or the best- and least-served parts of an area.
---

# Market scan

List every business of one type around a place, each measured by the market in a ring around it, and pick out the ones worth a closer look.

## Before running anything

1. **The center.** A full street address with its city, state and ZIP code, or a 5-digit ZIP code. For a town or a city, pass its latitude and longitude, with a `label`.
2. **The business type.** One key from `business_types`.
3. **How far.** `radius_miles` is 1, 2, 3, 5, 10, 15 or 25 (5 if not given). Each business is measured in a 1, 3 or 5-mile ring around it (`ring_miles`, 3 if not given).
4. **Which businesses.** `only: "independents"` for acquisition targets, `only: "chains"` for the chains, or `brand` for one chain's locations.
5. **The order.** `sort_by` one of `spendPerLocation` (household spending per competitor), `spendPerHousehold`, `medianIncome`, `incomeGrowth`, `households`, `daytimePop`, `competitors` (fewest first) or `distance` (the default).
6. **What it costs.** One action. It costs nothing when nothing is found, or when the same center and type were run in the last 12 hours.

## Run it

Call `market_report`. Keep `limit` to what the person will read: 25 by default, 100 at most.

## Present it

1. Lead with the count: how many were found, how many are chains and how many independents, and the biggest chains.
2. Then a table of the top businesses in the chosen order: name, miles from the center, households in the ring, median household income, spending per location, competitors in the ring and income growth.
3. Point out the two or three that stand out, and why, against the state figures in the report.
4. Offer next steps: a `site_report` on one or two of them (one action each), or `compare_sites` for two or three.

## House rules

- Present the figures as Groundwork's estimates and keep their units: dollars a year, and shares where 0.25 means 25%.
- Listings can miss or double-count businesses, and survey figures have margins of error.
- Describe places only by these market figures. Never characterize an area or its residents by race, ethnicity, religion, national origin, sex, disability or family status, and don't call an area good, bad, safe, rough or desirable.
- Close with the report's `notices`: its data licenses ask for them wherever the figures are shown.
