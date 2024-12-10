
<a href="https://colab.research.google.com/drive/1twrwcb6CHYkFoP0g9dKTlLL0-mTFEBnY?usp=sharing" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>


# Spatial Analysis and Web GIS Visualization of Urban-Rural Remote Work Migration Trends Pre/Post-COVID

## Overview
This project examines the impact of the COVID-19 pandemic on remote work trends and migration between urban and rural areas in the United States. Utilizing geostatistical methods and an interactive Web GIS platform, the analysis explores temporal and spatial dynamics in wage levels, occupational sector changes, and geographic migration patterns.

The objective is to provide actionable insights for policymakers and stakeholders addressing economic disparities and transformations in urban-rural dynamics in a post-COVID era.

---

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

- ### 2. **PDF output**
The [pdf](https://github.com/ArcturusMajere/finalgeog/blob/main/final.pdf) documents the project workflow, including:
- Static Maps only
- functionality of animation is NULL

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


## Project Highlights
- **Data Sources**: American Community Survey (ACS) data (2016–2022) and TIGRIS shapefiles via PyGRIS.
- **Geostatistical Analysis**: Explores wage migration and geographic shifts in remote work intensity.
- **Web GIS**: Implements an interactive platform for visualizing remote work migration, wage disparities, and sectoral transitions using distributive flow maps.
- **Visualization**: Combines static, animated, and interactive maps to display data insights effectively.



## How to Use This Repository
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/ArcturusMajere/finalgeog.git

### Open the Jupyter Notebook
Review the detailed workflow by opening the `updated_final2.ipynb` file.

# Bibliography of Datasets

This section lists all datasets used in the project, including their sources and descriptions.

---

## 1. **American Community Survey (ACS)**
- **Source**: U.S. Census Bureau
- **Description**: The ACS provides detailed demographic, social, economic, and housing data for U.S. counties. This project uses ACS data from 2016–2022 to analyze remote work trends, migration patterns, and wage levels.
- **Variables Used**:
  - `B08006_001E`: Total number of workers.
  - `B08006_017E`: Number of remote workers.
- **Access Method**: Retrieved using the `census` library and the Census API.
- **Website**: [ACS Data](https://www.census.gov/programs-surveys/acs)

---

## 2. **TIGRIS Shapefiles**
- **Source**: U.S. Census Bureau TIGER/Line Shapefiles
- **Description**: Geographic boundary files used to map U.S. counties and states. These shapefiles are essential for visualizing migration and remote work patterns across geospatial regions.
- **Access Method**: Accessed through the `pygris` library.
- **Website**: [TIGER/Line Shapefiles](https://www.census.gov/geographies/mapping-files/time-series/geo/tiger-line-file.html)

---

## 3. **PyGRIS County Boundaries**
- **Source**: Walker Data's PyGRIS Library
- **Description**: Provides pre-processed geographic shapefiles for counties in the U.S., optimized for use in Python. Used in this project for mapping and geospatial analysis.
- **Access Method**: Accessed via the `counties` function in the `pygris` library.
- **Website**: [PyGRIS](https://walker-data.com/pygris/)

---

## 4. **State and FIPS Codes**
- **Source**: `us` Python Library
- **Description**: Includes metadata such as state abbreviations and Federal Information Processing Standards (FIPS) codes, which are used to link Census data with geographic regions.
- **Access Method**: Accessed through the `us` library in Python.
- **Website**: [US Library](https://github.com/unitedstates/python-us)

---

## 5. **WFH Research**
- **Source**: Work-from-Home Research Project
- **Description**: Data on remote work trends and their economic and societal impacts. This project leverages insights from the WFH Research team to contextualize findings on remote work migration.
- **Access Method**: Insights and data accessed via the project website.
- **Website**: [WFH Research](https://wfhresearch.com/project-team/)

---

## 6. **USDA Rural Classifications**
- **Source**: U.S. Department of Agriculture Economic Research Service (ERS)
- **Description**: Data and classifications for defining rural and urban areas in the United States. These classifications are critical for analyzing urban-rural migration trends and understanding economic and demographic shifts.
- **Access Method**: Accessed via the USDA ERS website.
- **Website**: [USDA Rural Classifications](https://www.ers.usda.gov/topics/rural-economy-population/rural-classifications)

---

## 7. **Interactive GIS Data Tools**
- **Source**: Folium and Plotly Libraries
- **Description**: Generated maps and visualizations incorporating Census and TIGRIS shapefile data. Interactive maps allow exploration of migration and remote work trends.
- **Access Method**: Created programmatically within the Jupyter Notebook.
- **Tools**:
  - [Folium](https://python-visualization.github.io/folium/)
  - [Plotly](https://plotly.com/)


---

## Notes
- All datasets used are publicly accessible and were processed in compliance with the terms of use specified by their respective sources.
- For detailed information on preprocessing and integration, refer to the [Notebook](https://github.com/ArcturusMajere/finalgeog/blob/main/updated_final2.ipynb).

