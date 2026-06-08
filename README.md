# Retail Data Pipeline (Databricks)

## Overview
This project is a simple end-to-end data pipeline built using Databricks.  
The goal was to understand how real data engineering pipelines are designed using the Bronze, Silver, and Gold architecture.

---

## What this project does

- Takes raw data and stores it as Bronze tables  
- Cleans and formats the data in the Silver layer  
- Creates useful business insights in the Gold layer  

---

## Pipeline Flow

Bronze → Silver → Gold

### Bronze Layer
- Created sample datasets (customers and orders)
- Stored them as Delta tables using PySpark

### Silver Layer
- Converted data types
- Removed duplicate records
- Joined customer and order data to create enriched dataset

### Gold Layer
- Aggregated data to calculate total sales per customer
- Identified top customers based on revenue

---

## Tech Stack

- Databricks
- PySpark
- Delta Lake

---

## Key Highlights

- Used Spark DataFrames for transformations  
- Implemented basic ETL pipeline structure  
- Worked with managed Delta tables  
- Applied joins and aggregations  

---

## Future Improvements

- Add Auto Loader for incremental data ingestion  
- Schedule the pipeline using Databricks Jobs  
- Optimize performance using partitioning  

---

## Why I built this

I built this project to get hands-on experience with Databricks and understand how real-world data pipelines work.  
It helped me understand data ingestion, transformation, and how to structure pipelines properly.
