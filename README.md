# Potential Khas Land for EV Charging Stations – Dhaka City

An interactive web map of khas (government-owned) land plots in Dhaka City
screened as potential sites for electric vehicle (EV) charging stations.

**Live map:** https://israqsadmani.github.io/EV_Charging_Station_Suitability_Map/

## Summary
726 khas land plots were screened. 49 were found suitable and rated by suitability class:

| Class        | Colour | Plots |
|--------------|--------|-------|
| High         | Green  | 11    |
| Medium       | Orange | 17    |
| Low          | Red    | 21    |
| Not suitable | Grey   | 677   |

## Screening criteria
- **Minimum area:** at least 4 katha (1 katha = 66.8902 m²). Smaller adjoining plots were kept where together they form a usable site.
- **Accessibility:** access from a major road.
- **Vacancy:** vacant or easily cleared; not built up or in restricted use.

Plots were assessed manually in ArcGIS. Most exclusions were for size (409 plots),
followed by existing structures, restricted use and lack of road access.

## Map features
- Plots labelled by JL_Sh_Plot (JL No_Sheet No_Plot No)
- Click a plot to see mauza, JL/sheet/plot number, area (katha), current use and administrative units
- Show or hide each suitability class; the Not suitable layer is off by default
- Search by JL_Sh_Plot or mauza name, with suggestions while typing
- Basemaps: Google Streets, Google Satellite, Google Hybrid, OpenStreetMap, Esri World Imagery

## Data
Plot boundaries from RS (Revisional Survey) mauza maps, Dhaka District.

## Built with
[Leaflet](https://leafletjs.com/), hosted on GitHub Pages.
