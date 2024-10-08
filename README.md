# Greenhouse Gas Emissions Data Analysis and Dashboard

This repository contains Jupyter notebooks for analyzing and visualizing greenhouse gas (GHG) emissions data, specifically focusing on CO₂ and methane (CH₄) emissions. Additionally, it includes an interactive dashboard built with **Dash** for dynamic visualization of the emissions data across different regions and time periods.

## Project Overview

The project focuses on exploring, visualizing, and interacting with global greenhouse gas emissions data through:
- CO₂ Emissions Data (2000 - 2023)
- Methane Emissions Data (1999 - 2016)

It features a dashboard for visualizing emissions data on a map, providing insights into different regions over time.

## Notebooks

1. **`2000,2023 CO2.ipynb`**
   - Analyzes CO₂ emissions from the **odiac-ffco2-monthgrid-v2023** collection.
   - Includes code to query data using the `STAC_API_URL` and visualize it with Folium and Dash.

2. **`1999, 2016 methane.ipynb`**
   - Analyzes methane emissions from the **tm54dvar-ch4flux-monthgrid-v1** collection.
   - Queries methane data and visualizes results with Folium and Dash.

## Dashboard

The project includes a **Dash**-based interactive dashboard for dynamic visualization of the emissions data:

- **Select Region**: Choose from predefined regions (e.g., Los Angeles, Texas, Egypt) or input custom coordinates.
- **Select Time**: Choose a year and month to view CO₂ or CH₄ emissions for the selected region.
- **Map Visualization**: The dashboard generates a map showing the selected region and colors it based on the level of emissions (Low, Moderate, or High).

### Running the Dashboard

To run the dashboard locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Machine.git
