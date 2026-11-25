---
name: site-comparison
description: Compare two or three U.S. sites side by side with Groundwork, with each figure's percentile among U.S. neighborhoods and a 0 to 100 similarity score for each pair. Use when someone is choosing between locations, or looking for a site like one that already does well.
---

# Site comparison

Put two or three sites side by side and say which are alike, where they differ, and what that means for the business.

## Before running anything

1. **The sites.** Two or three, each a full street address with its city, state and ZIP code, a 5-digit ZIP code, or a latitude and longitude with a `label`.
2. **The business type.** One key from `business_types`.
3. **The ring.** 1, 3 or 5 miles (3 if not given), the same for every site.

Comparisons through Groundwork aren't counted. If Groundwork answers that the account's plan doesn't include the connector, say so plainly: plans are managed on the Groundwork website.

## Run it

Call `compare_sites` with the sites, `business_type` and `ring_miles`.

## Present it

1. A table with one row per figure and one column per site, each value with its percentile among U.S. neighborhoods (50 is typical).
2. The similarity score for each pair, in the report's own words, with the measures most and least alike.
3. Three or four sentences on what the differences mean for this business: more households, more spending per household, fewer businesses of the type nearby, faster income growth.
4. When one site is the one that already works, say which of the others is most like it, and where it falls short.

## House rules

- Present the figures as Groundwork's estimates and keep their units: dollars a year, and shares where 0.25 means 25%.
- Nearby businesses are shown but not scored in the similarity score; say so if it matters.
- Don't name or guess where the data comes from. Asked, say Groundwork compiles it from public and licensed sources.
- Describe places only by these market figures. Never characterize an area or its residents by race, ethnicity, religion, national origin, sex, disability or family status, and don't call an area good, bad, safe, rough or desirable.
- Close with the report's `notices`: its data licenses ask for them wherever the figures are shown.
