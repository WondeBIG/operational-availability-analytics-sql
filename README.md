# Delivery Operations Availability Analysis - SQL Queries
## Overview

This repository contains SQL queries designed to analyze delivery operations availability, focusing on:
* Downtime & Uptime Analysis due to operational delays.
* Weather Impact on Deliveries & Service Availability.
* Regulatory Constraints Affecting Deliveries.

Each query is structured for scalability, performance optimization, and seamless integration with BI tools such as Power BI, Mode Analytics, Tableau, and Looker.

## Queries Included

## Facility Downtime & Uptime Analysis
Objective: Analyze facility downtime, uptime percentages, and affected packages to assess service disruptions.

## Key Metrics:
* Total Downtime Events & Duration (Seconds & HH:MM:SS Format).
* Operational Uptime (%) per Facility & Country.
* Number of Orders & Packages Affected.
Use Case: Identifying bottlenecks in service utilization and improving operational efficiency.

## Weather Impact on Deliveries
Objective: Quantify the impact of severe weather conditions (high winds) on orders, flights, and packages.

## Key Metrics:
* Max Wind Speed & Duration of High Winds (Minutes).
* Total Affected Facilities, Orders, and Packages.
* Disruption Ratios (Facilities, Orders, and Packages).
* Use Case: Predicting and mitigating weather-related delivery disruptions.

## Regulatory Constraints on Deliveries
Objective: Analyze delays and cancellations due to regulatory constraints on orders and flights.

## Key Metrics:
* Launch Delay (Minutes) between package commitment & flight launch.
* Order Delay (Minutes) between order confirmation & delivery.
* Regulatory Off-Nominal Events Affecting Orders & Flights.
* Use Case: Understanding compliance-related delays and optimizing logistics planning.

## Conclusion

These queries provide critical insights into delivery operations, covering downtime, weather disruptions, and regulatory constraints. By pre-aggregating necessary calculations, this dataset is ready for integration into BI tools for further analysis and visualization.

## Future Enhancements:
* Adding geospatial analytics for better impact assessment by region.
* Implementing machine learning models to predict disruptions based on historical trends.
