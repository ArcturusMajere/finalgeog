Mapping Remote Work Trends in U.S. Counties: A Spatial Analysis of Remote Work Intensity (2016–2022)
This notebook provides a spatial analysis of remote work trends across U.S. counties, using data from the American Community Survey (ACS) from 2016 to 2022.

Project Overview
The analysis in this notebook focuses on:

Data Collection: Fetching data from the ACS API on remote work hours and total work hours per county, then normalizing these values to show the proportion of remote work.
Geographic Mapping: Visualizing normalized remote work intensity on U.S. county maps using pygris and geopandas.
Visualization Options:
Static Grid: Displaying a series of annual maps in a grid format to easily compare remote work trends over the years.
Animated Visualization: Creating an animation of the maps to provide a dynamic view of temporal changes in remote work distribution.
Visualization Approach
two visualization approaches in this notebook:

1. Static Grid of Maps
The static grid displays each year’s map in a grid layout, allowing for side-by-side comparison across multiple years. This format is useful for quick, direct comparisons between specific years.

2. Animated Map Sequence
An animated sequence shows the progression of remote work intensity over time, providing a clear visualization of geographic and temporal patterns in remote work. This is ideal for understanding overall trends and seeing year-over-year shifts in a dynamic way.

Data Source
The data used in this analysis is sourced from the American Community Survey (ACS) 5-Year Estimates, accessed through the U.S. Census Bureau API. We retrieve data on total work hours and remote work hours per county from 2016 to 2022.

Requirements
To run this analysis, you will need:
