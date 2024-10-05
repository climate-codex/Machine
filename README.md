# Greenhouse Gas Emissions Data Analysis

This repository contains Jupyter notebooks for analyzing greenhouse gas (GHG) emissions data, specifically focusing on CO₂ and methane (CH₄) emissions over time using STAC and raster APIs.

## Project Overview

This project is dedicated to exploring and visualizing global greenhouse gas emissions data using geospatial data provided by APIs. We are working with:
- CO₂ Emissions Data (2000 - 2023)
- Methane Emissions Data (1999 - 2016)

## Notebooks

1. **`2000,2023 CO2.ipynb`**
   - Analyzes CO₂ emissions from the **odiac-ffco2-monthgrid-v2023** collection.
   - Queries data using the `STAC_API_URL` and visualizes results with Folium.
   
2. **`1999, 2016 methane.ipynb`**
   - Analyzes methane emissions from the **tm54dvar-ch4flux-monthgrid-v1** collection.
   - Queries data in a similar way and also visualizes the results using Folium and Matplotlib.

## API Usage

The data is accessed through two main APIs:
- **STAC API**: Provides metadata about geospatial assets.
- **RASTER API**: Provides access to raster-based geospatial data for analysis.

### Example API Query

Both notebooks use the following APIs:
```python
STAC_API_URL = "https://earth.gov/ghgcenter/api/stac"
RASTER_API_URL = "https://earth.gov/ghgcenter/api/raster"


## Dashboard

The project includes a **Dash**-based interactive dashboard for dynamic visualization of the emissions data:

- **Select Region**: Choose from predefined regions (e.g., Los Angeles, Texas, Egypt) or input custom coordinates.
- **Select Time**: Choose a year and month to view CO₂ or CH₄ emissions for the selected region.
- **Map Visualization**: The dashboard generates a map showing the selected region and colors it based on the level of emissions (Low, Moderate, or High).

### Running the Dashboard

To run the dashboard locally:
emissions (Low, Moderate, or High).
 
