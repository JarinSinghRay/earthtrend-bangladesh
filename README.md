# 🌍 Earth Trend Explorer: Bangladesh

### NASA Space Apps Challenge 2026 | Team TerraNova Labs 🇧🇩

[![NASA Space Apps Challenge](https://img.shields.io/badge/NASA-Space%20Apps%202026-blue)](https://www.spaceappschallenge.org/2026/)
[![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen)](https://earthtrend-bangladesh-7xae.vercel.app/)
[![React](https://img.shields.io/badge/React-19-blue)](https://react.dev/)
[![Vite](https://img.shields.io/badge/Vite-8-purple)](https://vite.dev/)
[![License](https://img.shields.io/badge/License-See%20Data%20Sources-lightgrey)](#-11-references--credits)

**Challenge:** Be An Earth System Trend Detective!

**🌐 Live Demo:** https://earthtrend-bangladesh-7xae.vercel.app/

**📂 GitHub Repository:** https://github.com/JarinSinghRay/earthtrend-bangladesh

---

## 📌 Table of Contents

- [Project Overview](#-1-project-overview)
- [Problem Statement](#-2-problem-statement)
- [Our Solution](#-3-our-solution)
- [Key Features](#-4-key-features)
- [NASA Data Sources](#-5-nasa-data-sources-used)
- [Geographic Data Sources](#-6-geographic-data-sources)
- [Team Members & Roles](#-7-team-members--roles)
- [Tools & Technologies](#-8-tools--technologies)
- [Installation & Setup](#-9-installation--setup)
- [AI Usage Disclosure](#-10-use-of-ai-disclosure)
- [Project Status & Limitations](#-11-project-status--limitations)
- [Presentation Videos](#-12-presentation-video-links)
- [References & Credits](#-13-references--credits)
- [Our Vision](#-14-our-vision)

---

## 🌎 1. Project Overview

| Information | Details |
|---|---|
| Project Name | Earth Trend Explorer: Bangladesh |
| Team Name | TerraNova Labs |
| Team Leader | Ahmed Afeef Murad |
| Country | Bangladesh 🇧🇩 |
| Competition | NASA Space Apps Challenge 2026 |
| Official Challenge | Be An Earth System Trend Detective! |
| Geographic Coverage | 8 Administrative Divisions |
| Observation Locations | 15 Locations |
| Climate Grid Cells | 54 Grid Cells |
| Analysis Period | 2001–2025 |
| Live Demo | [Visit Website](https://earthtrend-bangladesh-7xae.vercel.app/) |
| GitHub | [View Repository](https://github.com/JarinSinghRay/earthtrend-bangladesh) |

### About the Project

**Earth Trend Explorer: Bangladesh** is an interactive climate intelligence and environmental data visualization platform designed to investigate historical climate patterns and environmental changes across Bangladesh.

Bangladesh is highly exposed to climate-related challenges, including rising temperatures, changing rainfall patterns, extreme weather events, and environmental variations.

Understanding these changes requires reliable scientific datasets, geographical analysis, and accessible data visualization.

Our platform brings together NASA Earth science datasets, climate analysis, statistical methods, and interactive geographic visualization to make complex environmental information easier to explore and understand.

The project analyzes historical climate information from 2001 to 2025 using 54 selected Bangladesh climate grid cells and 15 supported observation locations across the country's 8 administrative divisions.

**Our mission is to transform Earth science data into meaningful insights that support climate awareness, scientific exploration, and data-driven environmental understanding.**

### Explore the Live Platform

🌐 https://earthtrend-bangladesh-7xae.vercel.app/

---

## ⚠️ 2. Problem Statement

Bangladesh faces several climate and environmental challenges that affect communities, agriculture, ecosystems, and natural resources.

Some major concerns include:

- Increasing temperature and changing seasonal patterns.
- Variations in rainfall distribution.
- Regional differences in climate conditions.
- Changes in vegetation and land surface temperature.
- Environmental pressure on agricultural and natural ecosystems.
- Limited public accessibility to understandable scientific climate information.

Although NASA provides extensive Earth observation and climate datasets, accessing, processing, and interpreting these datasets can be challenging for non-specialist users.

There is a need for an accessible platform that allows people to explore historical climate patterns, investigate regional differences, and understand environmental changes through scientific data.

### Our Challenge

How can NASA Earth science data be transformed into meaningful, interactive, and understandable information that helps people investigate climate trends across Bangladesh?

---

## 💡 3. Our Solution

Earth Trend Explorer: Bangladesh addresses this challenge through an interactive web-based climate exploration and visualization platform.

The platform combines climate time-series data, geographical information, Earth observation datasets, and statistical analysis to investigate environmental patterns across Bangladesh.

### Our Approach

1. Collect climate information from NASA Earth science sources.
2. Organize geographic information across Bangladesh's 8 administrative divisions.
3. Analyze historical climate information from 54 selected grid cells.
4. Explore climate patterns across 15 supported observation locations.
5. Process temperature and precipitation indicators.
6. Visualize historical patterns through interactive charts and maps.
7. Investigate climate variability, anomalies, trends, and statistical significance.

### Geographic Coverage

Our current application includes:

- 8 administrative divisions.
- 15 supported observation locations.
- 54 selected Bangladesh climate grid cells.
- 104 initial geographic bounding-box cells, filtered to 54 Bangladesh cells using a geographic mask.

**Important:** The application does not currently provide 64 individual district polygons or district area-weighted climate averages. Its geographic analysis is based on the documented 54-grid-cell dataset and 15 observation locations.

---

## 🚀 4. Key Features

### 4.1 Interactive Climate Dashboard

Explore Bangladesh climate information through an interactive dashboard with charts, visual indicators, and scientific summaries.

### 4.2 Temperature Analysis

Investigate historical temperature indicators:

- T2M – Mean air temperature.
- T2M_MAX – Maximum air temperature.
- T2M_MIN – Minimum air temperature.
- DTR – Diurnal Temperature Range.

### 4.3 Rainfall Analysis

Explore historical precipitation patterns, seasonal rainfall distribution, and rainfall anomalies.

### 4.4 Climate Trend Detection

Investigate historical environmental changes through statistical trend analysis.

### 4.5 Seasonal Climate Analysis

Explore seasonal climate variations, including:

- Pre-monsoon.
- Monsoon.
- Post-monsoon.
- Winter.

### 4.6 Geographic Climate Visualization

Explore Bangladesh's administrative divisions, observation locations, and 54 selected climate grid cells through interactive maps.

### 4.7 NASA Earth Observation Layers

Explore available NASA Earth observation map layers, including MODIS-related vegetation and land surface temperature imagery.

### 4.8 Climate Anomaly Exploration

Investigate unusually warm, cool, wet, or dry periods using historical climate records and anomaly indicators.

### 4.9 Statistical Analysis

The analytical workflow includes:

- Mann-Kendall trend testing.
- Sen's slope estimation.
- Trend-Free Pre-Whitening (TFPW).
- Benjamini-Hochberg False Discovery Rate (FDR) correction.
- Pearson and Spearman correlation analysis.
- Pettitt change-point testing.

### 4.10 Scientific Data Explorer

Explore available datasets, their scientific variables, spatial resolutions, temporal coverage, and integration status.

---

## 🛰️ 5. NASA Data Sources Used

NASA Earth science datasets form the scientific foundation of Earth Trend Explorer: Bangladesh.

The platform uses climate reanalysis data, satellite-derived environmental indicators, and NASA Earth observation services.

### 5.1 NASA POWER – MERRA-2 Climate Data

**Full Name:** Prediction Of Worldwide Energy Resources (POWER)

**Data Provider:** NASA Langley Research Center POWER Project / NASA Global Modeling and Assimilation Office (GMAO).

**Underlying Climate Product:** MERRA-2 Reanalysis.

**Official Website:** https://power.larc.nasa.gov/

**API Documentation:** https://power.larc.nasa.gov/docs/services/api/

**Dataset DOI:** https://doi.org/10.5067/7MCPBJ41Y0K6

**Dataset Type:** Meteorological and climate reanalysis data.

#### Climate Parameters

| Parameter | Description | Unit |
|---|---|---|
| T2M | Mean Air Temperature at 2 Meters | °C |
| T2M_MAX | Maximum Air Temperature at 2 Meters | °C |
| T2M_MIN | Minimum Air Temperature at 2 Meters | °C |
| DTR | Diurnal Temperature Range | °C |
| PRECTOTCORR | Corrected Total Precipitation | mm/day |
| Soil Wetness | Surface and Root-Zone Soil Wetness | Dataset-dependent |

#### Spatial and Temporal Coverage

- Native spatial resolution: 0.5° × 0.625°.
- Approximate grid-cell scale: 50–65 km.
- Selected Bangladesh grid cells: 54.
- Initial bounding-box grid cells: 104.
- Local climate analysis period: 2001–2025.
- NASA POWER API historical coverage: 1980 to near present, depending on parameter and availability.

#### How We Use NASA POWER Data

1. Retrieve meteorological information through NASA POWER.
2. Organize climate information into monthly time-series records.
3. Process local CSV datasets containing historical climate observations from the reanalysis product.
4. Recompute annual statistics from monthly records where appropriate.
5. Analyze temperature, precipitation, and diurnal temperature range.
6. Investigate seasonal patterns and historical anomalies.
7. Perform statistical trend analysis across the 54 selected Bangladesh grid cells.
8. Present the results through interactive visualizations.

**Data Transparency:** The repository includes a local historical CSV archive and NASA POWER API integration. Live API response verification and complete browser-based end-to-end verification should be considered separately from the existence of the integration code.

### 5.2 MODIS/Terra Land Surface Temperature – MOD11A2.061

**Dataset Name:** MODIS/Terra Land Surface Temperature/Emissivity 8-Day L3 Global 1km SIN Grid V061.

**Data Provider:** NASA Land Processes Distributed Active Archive Center (LP DAAC).

**Dataset DOI:** https://doi.org/10.5067/MODIS/MOD11A2.061

**Spatial Resolution:** 1 km.

**Temporal Resolution:** 8-day composite.

**Historical Coverage:** February 2000 to present, subject to product availability.

#### Scientific Variables

- Daytime Land Surface Temperature.
- Nighttime Land Surface Temperature.

#### How We Use This Dataset

- Explore land surface temperature information.
- Provide environmental context for climate exploration.
- Support visualization of satellite-derived surface temperature information.
- Investigate differences between daytime and nighttime land surface conditions.

**Integration Status:** Listed as a connected dataset in the application. Actual retrieval and processing of individual satellite granules should be distinguished from map-layer visualization.

### 5.3 MODIS/Terra Vegetation Indices – MOD13Q1.061

**Dataset Name:** MODIS/Terra Vegetation Indices 16-Day L3 Global 250m SIN Grid V061.

**Data Provider:** NASA LP DAAC.

**Dataset DOI:** https://doi.org/10.5067/MODIS/MOD13Q1.061

**Spatial Resolution:** 250 m.

**Temporal Resolution:** 16-day composite.

**Historical Coverage:** February 2000 to present, subject to product availability.

#### Scientific Variables

- NDVI – Normalized Difference Vegetation Index.
- EVI – Enhanced Vegetation Index.

#### How We Use This Dataset

- Explore vegetation-related environmental indicators.
- Provide vegetation context for environmental monitoring.
- Support visualization of satellite-derived vegetation information.
- Investigate changes in vegetation conditions.

**Integration Status:** Listed as a connected dataset in the application. Individual pixel-level processing should not be confused with displaying satellite imagery layers.

### 5.4 NASA Global Imagery Browse Services (GIBS)

**Full Name:** Global Imagery Browse Services.

**Provider:** NASA Earth Observing System Data and Information System (EOSDIS).

**Official Documentation:** https://earthdata.nasa.gov/eosdis/science-system-description/eosdis-components/gibs

**Service Type:** Web Map Tile Service (WMTS).

#### How We Use NASA GIBS

- Display NASA Earth observation imagery.
- Provide satellite imagery context on the interactive map.
- Support visualization of available MODIS-related environmental layers.
- Help users explore geographical and environmental conditions.

**Integration Status:** Used for map imagery and visualization. GIBS imagery tiles are not equivalent to independently processed raw scientific datasets.

### 5.5 NASA Common Metadata Repository (CMR)

**Full Name:** Common Metadata Repository.

**Provider:** NASA EOSDIS.

**Official API Documentation:** https://cmr.earthdata.nasa.gov/search/site/docs/search/api.html

**Purpose:** NASA dataset and collection metadata discovery.

#### How We Use CMR

- Search NASA scientific dataset metadata.
- Explore available Earth observation collections.
- Support dataset discovery and metadata verification.

**Integration Status:** Metadata search functionality is listed as tested in the application.

### 5.6 Additional NASA Datasets – Integration Roadmap

The following datasets are listed in the application as integration-in-progress or future sources. They should not be interpreted as fully integrated scientific inputs.

| Dataset | Provider | Purpose | Status |
|---|---|---|---|
| GPM IMERG Final Monthly V07 | NASA GES DISC | Monthly precipitation | Integration in progress |
| GPM IMERG Final Daily V07 | NASA GES DISC | Daily precipitation | Integration in progress |
| GLDAS Noah V2.1 | NASA GES DISC | Soil moisture | Integration in progress |
| OMI/Aura NO2 V003 | NASA GES DISC | Atmospheric NO2 | Integration in progress |
| AIRS V7.0 | NASA GES DISC | Atmospheric temperature and moisture | Coming soon |

These datasets are potential sources for future scientific analysis and additional environmental indicators.

---

## 🗺️ 6. Geographic Data Sources

Geographic datasets support the platform's administrative map and spatial visualization.

### 6.1 geoBoundaries – Bangladesh ADM1

**Dataset:** Bangladesh Administrative Boundaries (ADM1).

**Provider:** geoBoundaries.

**Geographic Coverage:** 8 administrative divisions of Bangladesh.

**Boundary ID:** BGD-ADM1-32408957.

**Source:** https://www.geoboundaries.org/api/current/gbOpen/BGD/ADM1/

**Underlying Boundary License:** CC0 1.0 Universal.

**License URL:** https://creativecommons.org/publicdomain/zero/1.0/

**Attribution:** geoBoundaries – https://www.geoboundaries.org/

#### How We Use This Dataset

- Display Bangladesh's 8 administrative divisions.
- Provide geographic context for climate visualization.
- Support interactive administrative boundary exploration.
- Help users understand the spatial distribution of climate information.

### 6.2 Natural Earth Geographic Data

**Dataset:** Natural Earth 1:10m Geographic Data.

**Provider:** Natural Earth.

**Source:** https://www.naturalearthdata.com/downloads/10m-cultural-vectors/

**License:** Public Domain.

**Terms of Use:** https://www.naturalearthdata.com/about/terms-of-use/

#### How We Use This Dataset

- Provide geographic coastline reference information.
- Support fallback geographic visualization.
- Help display Bangladesh's geographic outline.

### Geographic Analysis Coverage

| Geographic Component | Coverage |
|---|---|
| Administrative Divisions | 8 |
| Observation Locations | 15 |
| Selected Climate Grid Cells | 54 |
| Initial Bounding-Box Grid Cells | 104 |

**Important:** The application uses division-level administrative boundaries, not 64 individual district polygons. Climate grid-cell analysis is not equivalent to district-level area-weighted averaging.

---

## 👥 7. Team Members & Roles

### Team TerraNova Labs

Our team combines leadership, web development, data science, and design expertise to develop Earth Trend Explorer: Bangladesh.

| Team Member | Official Role |
|---|---|
| Ahmed Afeef Murad | Team Lead |
| Progga Mitra | Data Scientist |
| Shatta Dhar | Data Scientist |
| Jarin Singh Ray | Designer |
| Rakibul Hasan Bhuiyan | Designer |
| Mahfuz Hossain Sami | Designer |

### Individual Responsibilities

**1. Ahmed Afeef Murad — Team Lead**

- Led project development and team coordination.
- Developed the web application and interactive dashboard.
- Worked on frontend development and user experience.
- Worked on NASA data integration.
- Coordinated technical implementation and project presentation.

**2. Progga Mitra — Data Scientist**

- Climate data analysis.
- Statistical interpretation.
- Investigation of environmental trends.
- Data-driven insights.

**3. Shatta Dhar — Data Scientist**

- Scientific dataset analysis.
- Data processing and interpretation.
- Climate pattern investigation.
- Supporting data-driven findings.

**4. Jarin Singh Ray — Designer**

- User interface and visual design.
- Design elements and presentation materials.
- Supporting the platform's visual experience.

**5. Rakibul Hasan Bhuiyan — Designer**

- Visual design.
- Prototype and interface design.
- Presentation graphics and visual communication.

**6. Mahfuz Hossain Sami — Designer**

- System and visual design.
- Design structure and coordination.
- Supporting the overall project presentation.

---

## 💻 8. Tools & Technologies

The project uses modern web development technologies, geographic visualization libraries, and data visualization tools.

### Frontend Development

| Technology | Purpose |
|---|---|
| React 19 | Component-based user interface development |
| JavaScript (ES Modules) | Application logic and functionality |
| HTML5 | Web application structure |
| CSS3 | Interface styling |
| Vite 8 | Development server and build tooling |

### Mapping and Visualization

| Technology | Purpose |
|---|---|
| Leaflet 1.9 | Interactive geographic mapping |
| Recharts 3 | Interactive charts and data visualization |
| Lucide React | Interface icons |

### Styling and Development Tools

| Technology | Purpose |
|---|---|
| Tailwind CSS 3 | Utility-based styling |
| PostCSS | CSS processing |
| Autoprefixer | CSS vendor prefixing |
| Oxlint | Code linting |

### Data and Scientific Resources

- NASA POWER API.
- NASA MERRA-2 Reanalysis.
- NASA MODIS/Terra.
- NASA GIBS.
- NASA CMR.
- geoBoundaries.
- Natural Earth.
- CSV and GeoJSON datasets.

### Development and Deployment

- Git.
- GitHub.
- Visual Studio Code.
- Vercel.

**Repository:** https://github.com/JarinSinghRay/earthtrend-bangladesh

**Live Deployment:** https://earthtrend-bangladesh-7xae.vercel.app/

---

## ⚙️ 9. Installation & Setup

Follow these steps to run Earth Trend Explorer: Bangladesh locally.

### Prerequisites

- Node.js (compatible with Vite 8).
- npm.
- Git.
- Internet connection.

### Step 1: Clone the Repository

```bash
git clone https://github.com/JarinSinghRay/earthtrend-bangladesh.git
```

### Step 2: Navigate to the Project Directory

```bash
cd earthtrend-bangladesh
```

### Step 3: Install Dependencies

```bash
npm install
```

### Step 4: Start the Development Server

```bash
npm run dev
```

### Step 5: Open the Application

Open the local URL displayed in your terminal, usually:

```text
http://localhost:5173/
```

### Production Build

To create a production build:

```bash
npm run build
```

### Preview Production Build

```bash
npm run preview
```

### Live Application

https://earthtrend-bangladesh-7xae.vercel.app/

---

## 🤖 10. Use of AI Disclosure

AI tools were used as development and productivity assistance during the project.

We believe in transparent and responsible AI use. AI-assisted outputs were treated as supporting resources rather than substitutes for scientific data, independent validation, or team contributions.

### AI Tool Used

**ChatGPT – OpenAI**

**Official Website:** https://chatgpt.com/

#### Purpose of AI Assistance

- Understanding programming concepts.
- Supporting code explanations and debugging.
- Understanding NASA dataset documentation.
- Exploring data-processing approaches.
- Assisting with technical documentation.
- Improving project descriptions and presentation scripts.
- Supporting README preparation.

#### Example Prompts

**Prompt 1 – NASA Climate Data Analysis**

"Explain how NASA POWER climate datasets can be used to investigate historical temperature and rainfall trends across Bangladesh."

**Prompt 2 – Interactive Dashboard**

"Help design an interactive climate dashboard that presents geographical and environmental information using NASA Earth science datasets."

**Prompt 3 – Statistical Analysis**

"Explain how Mann-Kendall trend testing and Sen's slope estimation can be applied to historical climate time-series data."

**Prompt 4 – Geographic Visualization**

"Explain how administrative boundary data and climate grid cells can be represented using an interactive geographic map."

### Data Used with AI

The project uses scientific and geographic information from the datasets described in the NASA Data Sources and Geographic Data Sources sections.

AI assistance was used for development, research, explanation, and documentation.

AI-generated explanations were not treated as authoritative NASA scientific measurements or substitutes for statistical validation.

### AI Voice Generation

If an AI voice generator was used in the presentation, its actual tool name and purpose should be disclosed here.

**Tool Name:** [Add the actual tool name if used.]

**Purpose:** Presentation narration and voice assistance.

---

## 🔬 11. Project Status & Limitations

Scientific transparency is essential when analyzing Earth observation and climate datasets.

The following table distinguishes implemented application components from incomplete integrations and verification tasks.

### Implementation Status

| Component | Status |
|---|---|
| Web Application | Developed |
| Interactive Dashboard | Developed |
| React and Vite Frontend | Implemented |
| Leaflet Interactive Map | Implemented |
| 8 Administrative Division Boundaries | Implemented |
| 15 Observation Locations | Implemented |
| 54 Bangladesh Climate Grid Cells | Included in local dataset |
| Historical Climate CSV Archive | Available in repository |
| NASA POWER API Integration | Present in application |
| MODIS Dataset Entries | Listed as connected |
| NASA GIBS Map Imagery | Integrated for visualization |
| NASA CMR Metadata Search | Listed as tested |
| Live NASA API Verification | Requires final verification |
| Browser End-to-End Testing | Requires final verification |
| District Area-Weighted Average | Not Implemented |

### Scientific Analysis and Important Findings

The repository includes a climate analysis results summary for 2001–2025.

Some important findings from the local analysis include:

**Temperature Trends**

- National annual mean temperature shows a Sen's slope of approximately +0.03°C per decade.
- The annual mean temperature trend is not statistically significant (p = 0.761).
- Maximum and minimum temperature trends also require cautious interpretation.

**Rainfall Analysis**

- The rainfall series contains a significant discontinuity around 2015.
- The apparent long-term rainfall increase may be strongly influenced by this data discontinuity.
- Independent rainfall datasets should be used for verification before interpreting the increase as actual climate change.

**Seasonal Patterns**

- May is identified as the warmest month in the local analysis.
- January is identified as the coolest month.
- The monsoon season contributes a substantial proportion of annual rainfall.

**Statistical Analysis**

The project includes statistical methods such as Mann-Kendall testing, Sen's slope, autocorrelation checks, and FDR correction.

Detailed findings are available in:

`public/bangladesh_climate_ds/outputs/RESULTS_SUMMARY.md`

### Scientific Limitations

1. MERRA-2 is a reanalysis product, not direct weather-station measurement data.
2. The analysis covers a 25-year period, which is relatively short for assessing long-term climate change.
3. The selected grid cells have an approximate native spatial resolution of 0.5° × 0.625°.
4. The rainfall dataset exhibits a notable discontinuity around 2015.
5. Statistical significance should be interpreted with appropriate uncertainty and multiple-testing considerations.
6. Climate grid-cell analysis does not represent district area-weighted averages.
7. Satellite imagery visualization should not be confused with independently processed raw satellite measurements.
8. API integration code does not automatically establish that every live API request has passed end-to-end verification.

### Future Improvements

- Complete live NASA API verification.
- Perform full browser-based end-to-end testing.
- Integrate independent precipitation datasets such as GPM IMERG.
- Validate rainfall discontinuities using independent scientific sources.
- Improve spatial analysis and geographic resolution.
- Implement district-level area-weighted calculations using appropriate district polygons.
- Expand vegetation and land surface temperature analysis.
- Improve scientific uncertainty reporting and statistical validation.

---

## 🎥 12. Presentation Video Links

Our presentation videos introduce the problem, explain our solution, demonstrate the platform, and highlight the contributions of Team TerraNova Labs.

### 240-Second Project Presentation

**Duration:** 4 Minutes (240 Seconds)

**YouTube Link:** [INSERT 240-SECOND PRESENTATION LINK]

### 30-Second Final Video

**Duration:** 30 Seconds

**YouTube Link:** [INSERT 30-SECOND FINAL VIDEO LINK]

---

## 📚 13. References & Credits

We acknowledge NASA, scientific organizations, geographic data providers, and open-source communities for their valuable datasets, scientific documentation, and development resources.

### NASA Scientific Resources

**1. NASA POWER**

https://power.larc.nasa.gov/

**2. NASA POWER API Documentation**

https://power.larc.nasa.gov/docs/services/api/

**3. NASA MERRA-2**

https://gmao.gsfc.nasa.gov/reanalysis/MERRA-2/

**4. MODIS/Terra Land Surface Temperature – MOD11A2.061**

https://doi.org/10.5067/MODIS/MOD11A2.061

**5. MODIS/Terra Vegetation Indices – MOD13Q1.061**

https://doi.org/10.5067/MODIS/MOD13Q1.061

**6. NASA Global Imagery Browse Services (GIBS)**

https://earthdata.nasa.gov/eosdis/science-system-description/eosdis-components/gibs

**7. NASA Common Metadata Repository**

https://cmr.earthdata.nasa.gov/search/site/docs/search/api.html

**8. NASA GPM IMERG**

https://gpm.nasa.gov/data/imerg

**9. NASA GLDAS**

https://ldas.gsfc.nasa.gov/

**10. NASA Earthdata**

https://www.earthdata.nasa.gov/

### Geographic Data Resources

**11. geoBoundaries**

https://www.geoboundaries.org/

**12. geoBoundaries GitHub**

https://github.com/wmgeolab/geoBoundaries

**13. Natural Earth**

https://www.naturalearthdata.com/

### Open-Source Technologies

- React: https://react.dev/
- Vite: https://vite.dev/
- Leaflet: https://leafletjs.com/
- Recharts: https://recharts.org/
- Lucide React: https://lucide.dev/
- Tailwind CSS: https://tailwindcss.com/
- PostCSS: https://postcss.org/
- Autoprefixer: https://github.com/postcss/autoprefixer
- Oxlint: https://oxc.rs/docs/guide/usage/linter.html
- Git: https://git-scm.com/
- GitHub: https://github.com/
- Vercel: https://vercel.com/

### Credits and Attribution

We acknowledge:

- NASA and its scientific teams for Earth observation and climate data.
- NASA POWER and NASA GMAO for climate reanalysis resources.
- NASA LP DAAC for MODIS scientific datasets.
- NASA EOSDIS for GIBS imagery and metadata services.
- geoBoundaries for administrative boundary resources.
- Natural Earth for geographic reference data.
- Open-source developers and maintainers for the libraries used in this application.

All third-party datasets, imagery, code libraries, and other resources remain subject to their respective licenses and attribution requirements.

---

## 🌱 14. Our Vision

Climate change is not just a scientific concept. It is a reality that affects communities, agriculture, ecosystems, and future generations.

We believe that understanding environmental change begins with understanding scientific data.

Through **Earth Trend Explorer: Bangladesh**, Team TerraNova Labs aims to transform complex NASA Earth science information into accessible, meaningful, and interactive insights.

Our vision is to encourage climate awareness, promote scientific curiosity, and support data-driven environmental understanding across Bangladesh.

### Explore the Trends. Understand the Changes. Build a Sustainable Future.

---

**Project:** Earth Trend Explorer: Bangladesh

**Team:** TerraNova Labs

**Competition:** NASA Space Apps Challenge 2026

**Country:** Bangladesh 🇧🇩

**Live Demo:** https://earthtrend-bangladesh-7xae.vercel.app/

**GitHub Repository:** https://github.com/JarinSinghRay/earthtrend-bangladesh
