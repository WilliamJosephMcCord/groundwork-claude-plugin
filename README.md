# Groundwork for Claude

Groundwork measures the market around any U.S. location for people buying, opening or running local businesses: residents, households, incomes, household spending on the business type, competitors, jobs, traffic and growth. This plugin connects Claude to your Groundwork account and adds three skills that turn Groundwork's reports into finished work.

## What's inside

- **The Groundwork connector** (`https://www.groundworkdemographics.com/mcp`), with five tools:
  - `site_report`: the market around one site in 1, 3 and 5-mile rings, with the nearest competitors by name. One action.
  - `market_report`: every business of one type within up to 25 miles, each measured by the market around it. One action.
  - `compare_sites`: two or three sites side by side, with percentiles and a similarity score. One action per site.
  - `account_status` and `business_types`: free.
- **Skills:**
  - `site-memo`: a one-page memo on a site.
  - `market-scan`: a shortlist of businesses to buy, or the least-served spots in an area.
  - `site-comparison`: which sites are alike, and where they differ.

## Getting started

1. Install the plugin, then connect Groundwork from the plugin's Connectors tab.
2. Log in to your Groundwork account when asked, and choose Allow.
3. Ask, for example: "Write a site memo for collision repair at 1500 Polaris Pkwy, Columbus, OH 43240."

You need a Groundwork account. Reports spend actions from your Groundwork plan, the same as on the website; asking again about a place within 12 hours costs nothing.

## What it sends

The plugin talks only to Groundwork, at `https://www.groundworkdemographics.com/mcp`, signed in as your account. It sends what each report needs: the places you ask about (street addresses, ZIP codes, or latitudes and longitudes) and the business types. It never sends your conversation. Groundwork matches street addresses with the U.S. Census Bureau's public address records. It keeps a record of the reports run on your account, as it does for reports run on the website. More in the privacy policy below.

## Links

- How it works: https://www.groundworkdemographics.com/assistants
- Privacy: https://www.groundworkdemographics.com/privacy
- Terms: https://www.groundworkdemographics.com/terms
- Help: inquiries@groundworkdemographics.com

This product uses the Census Bureau Data API but is not endorsed or certified by the Census Bureau. Business listings come with licenses of their own: https://www.groundworkdemographics.com/credits
