Mapping Remote Work Trends in U.S. Counties: A Spatial Analysis of Remote Work Intensity (2016–2022)

Welcome to the repository for my final project for GEOG 593. This project focuses on mapping remote work trends across U.S. counties, using data from the American Community Survey (ACS) from 2016 to 2022. Below you'll find information about the project, installation instructions, and resources used.

Project Overview

The analysis in this project aims to provide a spatial understanding of remote work trends across U.S. counties. The goal is to visualize normalized remote work intensity on maps, allowing users to explore how remote work has evolved over time. The project uses both static and animated visualizations to present these trends in an accessible way.

Features

Interactive and static map visualizations of remote work intensity.

Animated visualization showing temporal changes in remote work distribution from 2016 to 2022.

Mobile-friendly user experience.

Data Sources

Data from authoritative sources, including the American Community Survey (ACS) 5-Year Estimates, accessed through the U.S. Census Bureau API, is used for the project. The data includes remote work hours and total work hours per county from 2016 to 2022.

Installation

To use or modify the remote work visualization experience, you will need to have access to Python and Jupyter Notebooks. Follow these steps:

Clone the repository to your local machine:

git clone https://github.com/ArcturusMajere/finalgeog.git

Ensure you have the required Python libraries installed. You can install them using the following command:

pip install -r requirements.txt

Obtain a U.S. Census API key to access ACS data.

Usage

Open the MappingACS.ipynb notebook in Jupyter Notebook or Jupyter Lab.

Customize any parameters as needed, such as the years to analyze or the visualization settings.

Run the notebook to generate both static and animated visualizations of remote work trends.

For detailed usage instructions, please refer to the docs/usage.md file in the repository.

Mapping Remote Work Notebook

The project includes a Jupyter Notebook named MappingACS.ipynb, which provides a demonstration of mapping remote work trends across U.S. counties using Python.

MappingACS.ipynb Overview

The notebook uses various Python libraries to process and visualize ACS data. It includes steps for:

Data Collection: Fetching data from the ACS API on remote work hours and total work hours per county, then normalizing these values to show the proportion of remote work.

Geographic Mapping: Visualizing normalized remote work intensity on U.S. county maps using pygris and geopandas.

Visualization Options:

Static Grid: Displaying a series of annual maps in a grid format to easily compare remote work trends over the years.

Animated Visualization: Creating an animation of the maps to provide a dynamic view of temporal changes in remote work distribution.

This notebook serves as the core component of the project, providing insights into the spatial and temporal dynamics of remote work in the United States.

Challenges & Considerations

Data Compatibility: Ensuring that all data sources were properly formatted and compatible with geographic mapping tools.

ACS Data Processing: Handling large datasets from ACS required careful preprocessing to ensure accuracy and efficiency in mapping.

Visualization Performance: Creating smooth animations while maintaining data accuracy required optimization of map rendering and data handling.

Future Enhancements

Expand the analysis to include other factors that may correlate with remote work trends, such as internet access or industry composition.

Improve the resolution of the geographic mapping to provide more localized insights.

Add interactive components to the animations to allow users to explore specific regions in more detail.

Contributing

Contributions are welcome! If you find an issue or have an idea for an enhancement, feel free to open an issue or submit a pull request.

License

This project is licensed under the MIT License - see the LICENSE file for details.

Contact

For any questions or suggestions, please contact me at [your-email@example.com].

