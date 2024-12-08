"Spatial Analysis and Web GIS Visualization of Urban-Rural Remote Work Migration Trends Pre/Post-COVID"



## Overview
This project examines the impact of the COVID-19 pandemic on remote work trends and migration between urban and rural areas in the United States. Utilizing geostatistical methods and an interactive Web GIS platform, the analysis explores temporal and spatial dynamics in wage levels, occupational sector changes, and geographic migration patterns.

The objective is to provide actionable insights for policymakers and stakeholders addressing economic disparities and transformations in urban-rural dynamics in a post-COVID era.

## Key Components
### 1. **Annotated Bibliography**
The [Annotated Bibliography](https://github.com/ArcturusMajere/finalgeog/blob/main/appendix%20A.pdf) offers a comprehensive review of literature related to:
- Remote work trends.
- Urban-rural migration dynamics.
- Wage disparities influenced by the pandemic.

### 2. **Jupyter Notebook**
The [Notebook](https://github.com/ArcturusMajere/finalgeog/blob/main/updated_final2.ipynb) documents the project workflow, including:
- Data collection and preprocessing.
- Temporal and spatial analysis of remote work trends.
- Visualization of urban-rural migration patterns.
- Development of the Web GIS platform.

## Project Highlights
- **Data Sources**: American Community Survey (ACS) data (2016–2022) and TIGRIS shapefiles via PyGRIS.
- **Geostatistical Analysis**: Explores wage migration and geographic shifts in remote work intensity.
- **Web GIS**: Implements an interactive platform for visualizing remote work migration, wage disparities, and sectoral transitions using distributive flow maps.
- **Visualization**: Combines static, animated, and interactive maps to display data insights effectively.

## Table of Contents
1. [Introduction](#introduction)
2. [Literature Review](#literature-review)
3. [Remote Work Trends (2016–2022)](#remote-work-trends-2016–2022)
4. [Mapping Remote Work Trends](#mapping-remote-work-trends)
5. [Urban-Rural Migration Analysis](#urban-rural-migration-analysis)
6. [Web GIS Development](#web-gis-development)
7. [Findings and Report](#findings-and-report)

## How to Use This Repository
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/ArcturusMajere/finalgeog.git
## How to Use This Repository

### Open the Jupyter Notebook
Review the detailed workflow by opening the `updated_final2.ipynb` file.

### Explore the Annotated Bibliography
Access `appendix A.pdf` for the literature review.

### Run the Notebook
1. Ensure Python dependencies are installed (`census`, `us`, `pygris`, etc.).
2. Modify parameters to replicate or extend analyses.

---

## Dependencies

This project requires the following Python libraries and tools to function properly:

### Core Libraries
- **matplotlib**: For static and animated data visualizations.
- **seaborn**: Enhances data visualization with more refined styles and plots.
- **pandas**: Essential for data manipulation and analysis.
- **geopandas**: For geospatial data manipulation and integration.
- **pygris**: Facilitates fetching geographic shapefiles (e.g., county boundaries).
- **numpy**: To support numerical operations.

### GIS and Geospatial Visualization
- **folium**: For creating interactive maps.
- **cartopy**: For advanced geospatial plotting.
- **shapely**: To manage and analyze geometric objects like lines and polygons.

### Data Sources and APIs
- **census**: For accessing U.S. Census data.
- **censusdata**: Provides additional tools for Census data retrieval.
- **us**: Facilitates working with U.S. state data (e.g., state abbreviations and FIPS codes).

### Web and Panel Visualization
- **panel**: Enables interactive dashboards and data exploration.
- **plotly**: Supports creating interactive plots and geospatial visualizations.

### Utility Libraries
- **requests**: For making HTTP requests to APIs.
- **time** and **os**: Handle timing operations and file management.

---

## Handling the API Key

To access U.S. Census data via the Census API, this project requires a valid API key. 


