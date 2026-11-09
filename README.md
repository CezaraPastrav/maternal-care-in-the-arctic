# Maternal care in the Arctic: exploratory views

> **Exploratory work in progress. Nothing here has been validated.**
> These views are early outputs from an ongoing research project. They are shared to prompt discussion, not to inform decisions. Do not use them for clinical, policy, planning, funding or media purposes, and do not cite them as findings. If you would like to use or discuss this work, please contact the owner of this repo.

An interactive page with five views of pregnancy, distance and care in Sweden's five northern counties (Norrbotten, Västerbotten, Jämtland, Västernorrland, Gävleborg), plus Yukon communities for telehealth:

- **Births and hospitals**: monthly births per kommun (2015–2026) over Swedish hospitals and delivery units.
- **Maternity catchments**: estimated travel time from each populated 1 km square to the care each complication needs, in summer, winter and snowstorm conditions.
- **Maternity burden**: estimated travel, nights away and help needed per pregnancy, by where you live.
- **Pregnancy journey**: one simulated pregnancy followed trip by trip, replayed from a second home for comparison.
- **Telehealth blackout atlas**: power and network outages set against births.

The page is a single self-contained file (`index.html`) that works offline. It was built for a multi-user touch table: open a view from any edge, move panels by their top bar, and twist or pinch with two fingers. It also works with a mouse.

## Data sources

Each view lists its sources and assumptions in its own notes. In short: births from Statistics Sweden (SCB) and the Yukon Bureau of Statistics; population grid from SCB; delivery units from IVO and regional reports; hospital list from GISCO/SKR, 1177 and Wikipedia; places from GeoNames; outage data from Energimarknadsinspektionen (Ei), PTS coverage data, Yukon utility filings and news reports. Travel times are estimated, not routed.

## Third-party software

[Leaflet](https://leafletjs.com) (BSD-2-Clause) and [D3](https://d3js.org) (ISC) are embedded in the page, as are the fonts Public Sans, IBM Plex Sans, IBM Plex Mono, Literata, Barlow Condensed and Source Sans 3 (SIL Open Font License).
