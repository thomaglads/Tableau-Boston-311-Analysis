# Tableau-Boston-311-Analysis
An interactive Tableau dashboard analyzing Boston's 311 service requests to identify operational trends, performance metrics, and geographic hotspots.

# Boston 311 Service Request Analysis

## Project Objective
This project uses Tableau to analyze the 311 service request data for the City of Boston. The goal was to build an interactive dashboard to identify key trends, measure departmental performance, and explore the geographic distribution of service requests to provide actionable insights for improving city operations.



Boston 311 Dashboard Screenshot
![WhatsApp Image 2025-06-10 at 14 09 50_f15e6812](https://github.com/user-attachments/assets/ffe3b5ca-823e-41cb-9415-927f816e8e27)

## Key Insights from the Dashboard

* **Geographic Hotspots:** The density map pinpoints the specific neighborhoods and areas with the highest concentration of service requests, allowing for targeted resource allocation.
* **Top Service Requests:** The dashboard identifies the "Top 10" most common issues reported by residents, highlighting areas like "Enforcement & Abandoned Vehicles" and "Street Cleaning" as major drivers of volume.
* **Departmental Performance:** The analysis of "Average Resolution Time by Department" reveals significant variations in efficiency, identifying which departments are quickest to resolve issues and which have the longest backlogs.
* **Volume Trends:** The time-series chart tracks the number of requests over time, making it possible to spot seasonal trends or spikes in activity that may correspond to specific events.

## Data Source
The dataset used is the publicly available **"311 Service Requests"** data, sourced directly from the City of Boston's official open data portal, **Analyze Boston**. The data is refreshed daily and contains detailed information on each service request, including open/closed dates, reason, department, and geographic coordinates.

## Tools & Techniques
* **Tableau Desktop:** Used for the entire workflow, including data connection, preparation, creating calculated fields, and building all interactive visualizations and the final dashboard.
* **Geospatial Analysis:** Implemented a density map (heatmap) using latitude and longitude data to visualize service request hotspots across the city.
* **Calculated Fields:** Created key metrics such as `Case Duration (Days)` using `DATEDIFF` functions to analyze operational performance.
* **Dashboard Actions & Filtering:** The dashboard is made fully interactive using filters and "Use as Filter" actions, allowing users to drill down into the data by selecting elements on the map or in other charts.

## Skills Demonstrated
* Data Visualization & Dashboard Design (Tableau)
* Geospatial Analysis (Mapping, Density Maps)
* Calculated Field Creation
* Time-Series Analysis
* Operational Performance Analysis
* Interactive Data Exploration

## Potential Business Impact
The insights from this dashboard can help the City of Boston to:
1.  **Optimize Resource Allocation:** Deploy resources like parking enforcement or street cleaning crews to the identified geographic hotspots.
2.  **Improve Departmental Efficiency:** Identify departments with longer resolution times to investigate potential bottlenecks and improve processes.
3.  **Proactive Planning:** Understand seasonal trends in requests to better plan for staffing and resource needs throughout the year.
