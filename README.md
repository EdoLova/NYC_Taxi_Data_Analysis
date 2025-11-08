# NYC Taxi Data Analysis

This project analyzes a sample of the New York City Taxi dataset using **PySpark** and **Python**.  
It focuses on large-scale data cleaning, spatial integration with borough boundaries, and computation of key operational metrics.

## Objectives
- Clean and integrate large-scale taxi trip data with NYC borough polygons (GeoJSON).
- Compute **utilization rate**, **average idle time**, and **intra/inter-borough flow metrics**.
- Explore temporal and spatial mobility patterns in New York City.

## Tools and Libraries
- **Python**, **PySpark**, **Pandas**, **Matplotlib**, **Shapely**
- Dataset: NYC Taxi trips sample + GeoJSON file of NYC boroughs

## Main Results
- Manhattan shows the highest taxi utilization and lowest idle time.
- Most trips are **intra-borough** within Manhattan, while **cross-borough** trips often connect to Queens and Brooklyn.
- The analysis demonstrates how Spark can handle large-scale urban mobility data efficiently.

## Author
Edoardo Lovato  
Université Claude Bernard Lyon 1 – Data Processing and Analytics (DPA)  
Academic Year 2025–2026
