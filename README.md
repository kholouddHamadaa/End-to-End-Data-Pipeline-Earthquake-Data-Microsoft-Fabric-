# End-to-End-Data-Pipeline-Earthquake-Data-Microsoft-Fabric-
Earthquake Data Engineering Project with Microsoft Fabric
 Project Overview

This project demonstrates how to build an end-to-end Data Engineering pipeline using Microsoft Fabric, covering data ingestion, transformation, and visualization.

The pipeline processes real-time earthquake events data from the USGS (United States Geological Survey) API and transforms it through a Medallion Architecture (Bronze → Silver → Gold) to enable advanced analytics and reporting.

 Technologies Used
Python
PySpark
Microsoft Fabric
Data Factory
Data Engineering (Lakehouse & Notebooks)
Power BI
 Architecture Overview

This project follows the Medallion Architecture:

 -Bronze Layer (Raw Data)
Ingests raw earthquake data directly from the USGS API
Stores data with minimal transformation
Acts as the source of truth
-Silver Layer (Cleaned & Transformed)
Cleans and standardizes the data
Handles missing/null values
Applies transformations and data enrichment
Prepares structured datasets for analysis
 -Gold Layer (Business-Ready Data)
Creates aggregated and analytics-ready datasets
Optimized for reporting and dashboards
Used in Power BI for visualization and insights

 Repository Contents
-Bronze Layer Notebook
Handles ingestion of raw earthquake data from the API
-Silver Layer Notebook
Performs data cleaning, transformation, and enrichment
-Gold Layer Notebook
Produces curated datasets for analytics and reporting

 Getting Started
Open Microsoft Fabric
Upload the notebooks to your workspace
Run the notebooks in order:
Bronze → Silver → Gold
Connect Power BI to the Gold layer for visualization

 Use Cases
Earthquake trend analysis
Geospatial insights
Real-time monitoring dashboards
Data engineering pipeline design using Fabric
