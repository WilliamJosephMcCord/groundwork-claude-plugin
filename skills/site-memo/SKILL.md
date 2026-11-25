---
name: site-memo
description: Write a one-page site memo for a U.S. location from a Groundwork site report, covering market size, household spending on the business type, nearby businesses of that type, traffic, growth and caveats. Use when someone asks to evaluate, size up or write up a specific address or site for a local business.
---

# Site memo

Turn one Groundwork site report into a short memo someone can act on.

## Before running anything

1. **Pin down the place.** Groundwork takes a full street address with its city, state and ZIP code, a 5-digit ZIP code, or a latitude and longitude. For a town, a city or a business known only by name, pass its latitude and longitude, with a `label` to call it by.
2. **Pin down the business type.** Use the closest key from `business_types`, such as `collision`, `tires`, `pizza`, `coffee` or `dentists`. When none fits closely, use the trade's "(all)" type and say so.

Reports through Groundwork aren't counted, so there's no need to ask before running one or to ration them. If Groundwork answers that the account's plan doesn't include the connector, say so plainly: plans are managed on the Groundwork website.

## Run it

Call `site_report` with the place and `business_type`. Add `ring_miles` only when the person wants a ring other than 1, 3 and 5 miles.

## Write the memo

Keep it to about a page, in this order:

1. **The site:** the place, the business type, and the rings measured.
2. **Market size:** residents, households and median household income in each ring, beside the state's.
3. **Demand:** what households spend a year on the business type, per household and in total.
4. **Nearby businesses:** how many of the type are listed in each ring, chains and independents, density against the state, and the nearest few by name and distance. Name them by their type ("12 tire shops within 3 miles"); don't call them competitors unless the person does.
5. **Access:** traffic on the roads at the site.
6. **Growth:** income growth, and new homes permitted in the county.
7. **Takeaways:** two or three plain sentences on what stands out, for better or worse.
8. **Check next:** what Groundwork doesn't cover, such as rents, zoning, the building itself and a site visit.

## House rules

- Present the figures as Groundwork's estimates and keep their units: dollars a year, and shares where 0.25 means 25%.
- Don't name or guess where the data comes from. Asked, say Groundwork compiles it from public and licensed sources.
- Mention a limit only where it changes how a figure reads; the report's `dataNotes` say where. Counts of nearby businesses come from map listings, which can miss or double-count businesses, so density against the state means more than an exact count.
- Describe places only by these market figures. Never characterize an area or its residents by race, ethnicity, religion, national origin, sex, disability or family status, and don't call an area good, bad, safe, rough or desirable.
- Close with the report's `notices`: its data licenses ask for them wherever the figures are shown.
