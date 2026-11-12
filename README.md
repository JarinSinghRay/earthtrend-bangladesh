# EarthTrend Bangladesh

An interactive climate-data exploration dashboard for Bangladesh. Explore trends, seasonal patterns, and environmental indicators across 15 locations in all 8 divisions, with maps, charts, data notes, and downloadable results.

## Features

- Six investigation areas: land-surface temperature, rainfall, vegetation, agriculture and soil, coastal change, and air and atmosphere.
- Interactive charts and maps for comparing locations, variables, seasons, and time periods.
- Data-source descriptions and scientific caveats alongside the visualizations.
- Local Bangladesh climate-analysis data and figures in `public/bangladesh_climate_ds/`.

Some data connections are still in progress. The app labels interim or demonstration data; do not treat those as fully connected satellite products.

## Run locally

### Requirements

- Node.js compatible with Vite 8
- npm

### Install and start

```bash
npm ci
npm run dev
```

Open the local URL printed by Vite in your browser.

### Other commands

```bash
npm run build    # Create a production build in dist/
npm run preview  # Preview the production build locally
npm run lint     # Run Oxlint
```

## Data

The project includes a Bangladesh climate dataset under `public/bangladesh_climate_ds/`, with raw NASA POWER monthly CSVs, processed tables, GeoJSON grid cells, dashboard JSON, and analysis figures. The accompanying `outputs/RESULTS_SUMMARY.md` describes the analysis and its findings.

The included 2001–2025 country analysis uses NASA POWER / MERRA-2 monthly temperature and precipitation data over 54 Bangladesh grid cells. NASA POWER is a reanalysis product, not a set of direct weather-station measurements. MODIS and other NASA data products are described in the dashboard; not every listed integration is connected to live data yet.

### Important interpretation notes

- The analysis identifies a large step change in NASA POWER precipitation around 2015. The results summary cautions that this may be a product artifact and recommends checking an independent dataset before interpreting rainfall trends as climate change.
- A reanalysis grid cell represents a regional area, not conditions at a specific farm or weather station.
- Land-surface temperature is not the same measurement as near-surface air temperature.
- Trends and correlations are statistical summaries and do not establish cause and effect.

## Tech stack

- React
- Vite
- Recharts
- Leaflet
- Tailwind CSS

## Project structure

```text
src/                         React application and styles
public/bangladesh_climate_ds/ Raw inputs, processed data, and analysis outputs
public/                       Static assets served by Vite
```
