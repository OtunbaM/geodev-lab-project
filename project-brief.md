 My project brief

## The question
Which wards in Osogbo LGA are located more than 5 km from a designated public market?

## Data Needed

- Osogbo LGA boundary
- Settlement of residents
- Public Market locations in Osogbo
- Road network data for map context

## Data Sources

- Ward boundaries — GRID3 — https://data.grid3.org/datasets/GRID3::grid3-nga-operational-wards-v3-0/about — GeoPackage — 190 MB
- Settlement extents — GRID3 — https://data.grid3.org/datasets/GRID3::grid3-nga-settlement-extents-v4-1/aboutg — GeoPackage—190 MB
- Markets in Nigeria — GRID3 — https://data.grid3.org/datasets/38201adf2211405989d83c546a58c8fb_0/explore?location=5.501262%2C6.858452%2C8 — GeoPackage — 3.4 MB
- OSM Roads — OSM via QuickOSM — extracted for Osogbo LGA
- OSM market place points — OSM via QuickOSM — extracted for Osogbo LGA

- ## What i would be building
1. Interactive Market Accessibility Map
- I will be using QGIS to visualize Osogbo’s wards, markets, and 5 km buffer zones.
- Highlight wards outside the buffer in red to show underserved areas.
- Add pop‑ups with ward names, population estimates, and distance to the nearest market.

2. Market Planning Dashboard, This will Include:
- Interactive map layers (markets, wards, roads)
- Charts showing percentage of population within/outside 5 km coverage
- Filters for market type (daily, periodic, wholesale).

3. Decision‑Support Outputs
- Accessibility Index: Score each ward based on proximity to markets.
- Priority List: Identify top 5 wards needing new market sites.

