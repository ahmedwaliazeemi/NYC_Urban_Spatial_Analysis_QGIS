# 🗺️ Spatial Analysis of NYC Urban Development: Brooklyn (QGIS)

<h2>🎯 Project Overview</h2>

This project conducts a comprehensive spatial analysis of the built environment in Brooklyn, New York, using QGIS. By leveraging the NYC MapPLUTO dataset and Community District boundaries, the analysis explores urban development patterns. Key tasks include calculating the average building year and lot size for each district and visualizing these metrics through choropleth maps to highlight the contrast between historic and developing neighborhoods.

<h2>✨ Key Features</h2>

Data Processing: Filtered the extensive NYC MapPLUTO dataset to isolate Brooklyn tax lots (Borough = 'BK').

Spatial Analysis: Performed spatial joins (Join Attributes by Location) to link individual tax lots with their corresponding Community Districts.

Feature Engineering: Calculated summary statistics, including the average Year Built and Lot Area per Community District.

Geospatial Visualization: Created choropleth maps to visualize the spatial distribution of building age and lot density.

CRS Management: Standardized projection to NAD83 / New York Long Island (ftUS) for accurate distance and area calculations.

<h2>🛠️ Technology Stack</h2>

<h2>>Core Software</h2>
GIS Software: QGIS (Quantum GIS)

# Data Sources
Primary Data: NYC MapPLUTO
Boundaries: NYC Community Districts
Projection: EPSG:2263 (NAD83 / New York Long Island)


<h2>🚀 How to View the Analysis</h2>

To view the full project and maps, you will need QGIS installed.

<h2>Clone the Repository:</h2>

git clone [https://github.com/YourUsername/NYC_Urban_Spatial_Analysis_QGIS.git](https://github.com/YourUsername/NYC_Urban_Spatial_Analysis_QGIS.git)
cd NYC_Urban_Spatial_Analysis_QGIS



<h2>Install QGIS:</h2>

Download and install the latest version of QGIS from the official website.

Open the Project:

Locate the .qgz file (QGIS Project) in the cloned folder.

Double-click to open it in QGIS.

Note: Ensure the relative paths to the shapefiles are maintained for layers to load correctly.

<h2>📂 Repository Contents</h2>

AHMEDWALI_20332545_ASSIGNMENT2.qgz: The main QGIS project file containing all layers, styling, and map layouts.

nycdwi.*: Shapefile components for NYC district water/boundaries.

assignment 2.docx: Detailed report documenting the methodology, spatial operations, and final map interpretations.
