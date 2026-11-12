# 🌍 Earth Trend Explorer: Bangladesh

### NASA Space Apps Challenge 2026 | Team TerraNova Labs 🇧🇩

[![NASA Space Apps Challenge](https://img.shields.io/badge/NASA-Space%20Apps%202026-blue)](https://www.spaceappschallenge.org/2026/)
[![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen)](https://earthtrend-bangladesh-7xae.vercel.app/)
[![Country](https://img.shields.io/badge/Country-Bangladesh-red)](https://www.nasa.gov/)

**Challenge:** Be An Earth System Trend Detective!

**🌐 Live Demo:** https://earthtrend-bangladesh-7xae.vercel.app/

---

## 📌 Table of Contents

- [Project Overview](#-1-project-overview)
- [Problem Statement](#-2-problem-statement)
- [Our Solution](#-3-our-solution)
- [Key Features](#-4-key-features)
- [NASA Data Sources](#-5-nasa-data-sources-used)
- [Team Members](#-6-team-members--roles)
- [Tools and Technologies](#-7-tools--technologies)
- [AI Usage Disclosure](#-8-use-of-ai-disclosure)
- [Project Status and Limitations](#-9-project-status-and-limitations)
- [Presentation Videos](#-10-presentation-video-links)
- [References and Credits](#-11-references--credits)
- [Our Vision](#-12-our-vision)

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
| Live Demo | [Visit Project](https://earthtrend-bangladesh-7xae.vercel.app/) |

### About the Project

**Earth Trend Explorer: Bangladesh** is a climate data analysis and visualization platform designed to explore environmental and climate trends across the 64 districts of Bangladesh.

Bangladesh is highly exposed to climate-related challenges, including rising temperatures, changing rainfall patterns, extreme weather events, and environmental variations.

Understanding these changes requires reliable scientific datasets, regional analysis, and accessible data visualization.

Our project aims to transform complex NASA Earth science data into understandable insights through an interactive web-based platform.

By exploring climate indicators such as temperature and precipitation, users can investigate historical environmental patterns and understand how climate conditions vary across different regions of Bangladesh.

**Our primary objective is to make Earth science data accessible, understandable, and useful for climate awareness and research.**

### Explore the Live Platform

🌐 **Live Website:** https://earthtrend-bangladesh-7xae.vercel.app/

---

## ⚠️ 2. Problem Statement

Bangladesh faces several environmental and climate-related challenges.

Some of the major concerns include:

- Increasing average temperatures.
- Changes in seasonal rainfall patterns.
- Regional variations in climate conditions.
- Environmental pressure on agriculture and natural resources.
- Limited accessibility to understandable scientific climate information.

Although NASA provides extensive Earth observation and climate datasets, accessing, processing, and interpreting these datasets can be challenging for non-specialist users.

There is a need for an accessible platform that allows users to explore climate indicators, investigate regional differences, and understand long-term environmental changes.

### Our Challenge

How can NASA Earth science data be transformed into meaningful, interactive, and understandable information that helps people investigate climate trends across Bangladesh?

---

## 💡 3. Our Solution

Earth Trend Explorer: Bangladesh addresses this problem through a web-based climate exploration and visualization platform.

The platform focuses on exploring climate information across Bangladesh's 64 districts.

Our approach includes:

1. Collecting climate-related information from NASA Earth science data sources.
2. Organizing geographical information for district-level exploration.
3. Processing temperature and precipitation indicators.
4. Visualizing climate information through interactive charts and maps.
5. Helping users investigate historical patterns and environmental variations.

### Our Geographic Approach

The project uses district representative-point analysis to organize climate information geographically across Bangladesh.

Each district is associated with a representative geographic location for point-based climate exploration.

**Important:** District representative-point analysis is not the same as district area-weighted averaging. Area-weighted district calculations are not currently implemented.

---

## 🚀 4. Key Features

### 4.1 Bangladesh's 64-District Exploration

Explore climate information associated with all 64 districts of Bangladesh.

### 4.2 Temperature Analysis

Investigate temperature indicators, including:

- Mean temperature.
- Maximum temperature.
- Minimum temperature.

### 4.3 Rainfall Analysis

Explore precipitation patterns and historical variations.

### 4.4 Interactive Dashboard

Access climate-related information through a web-based dashboard with interactive visualizations.

### 4.5 Geographic Visualization

Explore district-based climate information through geographic representation.

### 4.6 Climate Trend Exploration

Investigate historical changes in environmental indicators and compare patterns across locations.

### 4.7 Data-Driven Insights

Support climate awareness through the interpretation of scientific datasets and visual representations.

---

## 🛰️ 5. NASA Data Sources Used

NASA Earth science datasets are the scientific foundation of our project.

### 5.1 NASA POWER

**Full Name:** Prediction Of Worldwide Energy Resources

**Official Website:** https://power.larc.nasa.gov/

**API Documentation:** https://power.larc.nasa.gov/docs/services/api/temporal/monthly/

**Dataset Type:** Meteorological and solar-related data.

NASA POWER provides time-series data that can be used to investigate climate and environmental conditions.

#### Climate Parameters

| Parameter | Description | Unit |
|---|---|---|
| T2M | Temperature at 2 Meters | °C |
| T2M_MAX | Maximum Temperature at 2 Meters | °C |
| T2M_MIN | Minimum Temperature at 2 Meters | °C |
| PRECTOTCORR | Corrected Total Precipitation | mm/day for daily data; monthly mean daily rate for monthly data |

#### How We Use NASA POWER Data

Our intended data-processing workflow includes:

1. Selecting geographic coordinates associated with Bangladesh's districts.
2. Requesting climate parameters through the NASA POWER API.
3. Organizing the returned time-series data.
4. Processing temperature and precipitation indicators.
5. Preparing the data for visualization and regional exploration.

**Integration and verification:** Live API response verification and complete browser end-to-end validation remain pending.

NASA POWER API Documentation:  
https://power.larc.nasa.gov/docs/services/api/temporal/monthly/

### 5.2 Geographic District Boundary Data

**Purpose:** Geographic representation and district-level organization.

District boundary information is necessary to represent Bangladesh's 64 districts and associate geographical information with climate analysis.

#### How We Use Geographic Data

- Represent district locations.
- Organize climate information geographically.
- Support district-based exploration.
- Provide geographic context for data visualization.

**Dataset Source:** [Insert the actual district boundary dataset URL.]

**Attribution and License:** [Insert the original provider and license.]

### NASA Data Integrity

We distinguish between:

- NASA data retrieved and verified.
- NASA data integration under development.
- Geographic analysis implemented in the application.
- Statistical analysis that has not yet been validated.

We do not claim that unverified API responses or incomplete statistical calculations represent scientifically validated results.

---

## 👥 6. Team Members & Roles

### Team TerraNova Labs

Our team brings together leadership, web development, data science, and design expertise to develop Earth Trend Explorer: Bangladesh.

| Name | Official Role |
|---|---|
| Ahmed Afeef Murad | Team Lead |
| Progga Mitra | Data Scientist |
| Shatta Dhar | Data Scientist |
| Jarin Singh Ray | Designer |
| Rakibul Hasan Bhuiyan | Designer |
| Mahfuz Hossain Sami | Designer |

### Individual Responsibilities

**1. Ahmed Afeef Murad — Team Lead & Lead Web Developer**

- Led project development and team coordination.
- Developed the web application and interactive dashboard.
- Worked on frontend interface and user experience.
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

## 💻 7. Tools & Technologies

The project involves web application development, scientific data exploration, geographic visualization, and data analysis.

### Development Technologies

| Category | Technology |
|---|---|
| Frontend Development | [Insert actual framework] |
| Programming Language | [Insert actual language] |
| Backend Development | [Insert actual backend technology, if used] |
| Data Analysis | [Insert actual libraries used] |
| Data Visualization | [Insert actual charting library] |
| Geographic Visualization | [Insert actual mapping library] |
| Scientific Data Source | NASA POWER API |
| Version Control | Git |
| Code Hosting | GitHub |
| Deployment | Vercel |
| Development Environment | Visual Studio Code |

**Note:** Replace the bracketed entries with the technologies actually present in the submitted application and repository. Do not list technologies that were not used.

---

## 🤖 8. Use of AI Disclosure

AI tools were used as development and productivity assistance during the project.

### AI Tools Used

**1. ChatGPT**

**Purpose:**

- Understanding programming concepts.
- Supporting code development and debugging.
- Understanding NASA data documentation.
- Assisting with technical explanations.
- Preparing project documentation and README content.
- Improving presentation scripts and communication.

#### Example AI Assistance Prompts

**Prompt 1 – Climate Data Analysis**

"Explain how NASA POWER climate datasets can be used to investigate temperature and rainfall trends across Bangladesh."

**Prompt 2 – Dashboard Development**

"Help develop an interactive climate dashboard that presents district-level climate information using scientific datasets."

**Prompt 3 – Statistical Analysis**

"Explain how historical climate data can be processed and visualized to investigate environmental changes."

### AI-Generated Voice Assistance

An AI voice generation tool may be used for the project's presentation narration.

**Tool Name:** [Insert actual AI voice generator name.]

**Purpose:** English narration and presentation assistance.

### Data Used with AI

The project focuses on NASA Earth science data, particularly meteorological variables such as temperature and precipitation.

AI assistance was used to support development, research, explanation, and documentation.

AI-generated explanations were not treated as substitutes for NASA scientific measurements or independent statistical validation.

---

## 🔬 9. Project Status and Limitations

We believe scientific transparency is essential when working with Earth observation and climate datasets.

The following table identifies the current verification status of important project components.

| Component | Status |
|---|---|
| Web Application Development | Developed |
| Interactive Dashboard | Developed |
| District Representative-Point Analysis | Implemented approach |
| Live NASA API Response Verification | Pending |
| Browser End-to-End Testing | Pending |
| District Area-Weighted Average | Not Implemented |
| Full Statistical Significance Validation | Requires verification |

### Current Limitations

1. Live NASA API responses have not yet been fully verified.
2. Complete browser-based end-to-end testing remains pending.
3. District area-weighted climate averages have not been implemented.
4. Statistical significance of climate trends must be validated before presenting findings as scientifically significant.

### Future Improvements

- Complete NASA API integration and verification.
- Implement district area-weighted climate calculations.
- Introduce Mann-Kendall trend testing.
- Calculate linear regression slopes.
- Add confidence intervals and statistical significance indicators.
- Improve historical climate comparisons.
- Expand geographic and environmental data coverage.

---

## 🎥 10. Presentation Video Links

Our presentation videos introduce the problem, explain our solution, showcase the platform, and highlight the contributions of Team TerraNova Labs.

### 240-Second Project Presentation

**Duration:** 4 Minutes (240 Seconds)

**YouTube Link:** [INSERT 240-SECOND PRESENTATION LINK]

### 30-Second Final Video

**Duration:** 30 Seconds

**YouTube Link:** [INSERT 30-SECOND VIDEO LINK]

---

## 📚 11. References & Credits

We acknowledge NASA, scientific organizations, and open-source communities for providing valuable scientific data, documentation, and development resources.

### NASA Resources

1. **NASA Space Apps Challenge 2026**  
   https://www.spaceappschallenge.org/2026/

2. **Official Challenge — Be An Earth System Trend Detective!**  
   https://www.spaceappschallenge.org/2026/challenges/earth-system-trend-detective/

3. **NASA POWER Data Portal**  
   https://power.larc.nasa.gov/

4. **NASA POWER Monthly API Documentation**  
   https://power.larc.nasa.gov/docs/services/api/temporal/monthly/

5. **NASA Earthdata**  
   https://www.earthdata.nasa.gov/

### Development Resources

- GitHub: https://github.com/
- Visual Studio Code: https://code.visualstudio.com/
- Vercel: https://vercel.com/

### Additional Credits

- District boundary dataset: [Insert provider and source URL.]
- Third-party libraries: [Insert the actual libraries and their licenses.]
- Images and icons: [Insert original sources and attribution.]
- Research papers and publications: [Insert any sources actually consulted.]

We respect the licenses and attribution requirements of all third-party datasets, libraries, images, and resources used in this project.

---

## 🌱 12. Our Vision

Climate change is not just a scientific concept. It is a reality that affects communities, agriculture, ecosystems, and future generations.

We believe that making scientific information accessible is an important step toward understanding environmental change.

Through **Earth Trend Explorer: Bangladesh**, Team TerraNova Labs aims to make NASA Earth science data easier to explore and understand.

Our vision is to encourage climate awareness, promote scientific curiosity, and support data-driven environmental understanding across Bangladesh.

### Explore the Trends. Understand the Changes. Build a Sustainable Future.

---

<p align="center">

### 🌍 Team TerraNova Labs

**NASA Space Apps Challenge 2026**

**Be An Earth System Trend Detective!**

Made with dedication in Bangladesh 🇧🇩

**Live Demo:** https://earthtrend-bangladesh-7xae.vercel.app/

</p>
