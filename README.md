CO2e Emissions Analytics Dashboard (Continental USA)

Project Overview
This project presents an interactive Databricks dashboard that analyzes CO2-equivalent (CO2e) greenhouse gas emissions across the continental United States. 
The dashboard combines geospatial, per-capita, and aggregated views to identify emission hotspots, high-impact regions, and major contributors at both state and county levels.

Objectives
- Visualize the geographical distribution of CO2e emissions
- Compare regions using population-normalized (per-capita) emissions
- Identify top-emitting states and counties
- Support data-driven sustainability and environmental analysis

Data Description
The dataset includes:
- Geographic coordinates (latitude, longitude)
- County and state identifiers
- Population data
- Greenhouse gas emissions measured in million tons of CO2e

All data cleaning, type casting, and aggregations are performed using Databricks SQL.

Dashboard Visualizations

1. Location-Based CO2e Emissions (Point Map)
Metric: Total CO2e emissions (million tons)
Visualization: Point Map
Description: Displays the spatial distribution of emissions across the continental USA, highlighting regional emission hotspots.

2. Emissions per Person (Scatter Plot)
Metric: CO2e emissions divided by population
Visualization: Scatter Plot
Description: Normalizes emissions by population to allow fair comparison between regions and identify areas with disproportionately high per-capita emissions.

3. Top 10 States by Total Emissions (Pie Chart)
Metric: Sum of CO2e emissions by state
Visualization: Pie Chart
Description: Shows the relative contribution of the top 10 emitting states to overall emissions.

4. Top 10 Counties by Total Emissions (Bar Chart)
Metric: Total CO2e emissions
Visualization: Bar Chart
Description: Highlights counties with the highest absolute emissions, drawing attention to major local emission contributors.

Tools and Technologies
- Databricks
- Databricks SQL
- Apache Spark
- Data Visualization (Maps and Charts)
- GitHub for version control

Notes:
Databricks dashboards are stored as JSON files in the repository for version control. Visual previews of the dashboard can be found in the screenshots folder.
