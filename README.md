# End-to-End-E-Commerce-Data-Pipeline-Dashboard
# E-Commerce Analytics Platform (Databricks + Plotly)

This project demonstrates an end-to-end data analytics pipeline built using Databricks, Spark, Delta Lake, and Plotly to analyze e-commerce data and generate business insights.

---

## Project Overview

The goal of this project is to transform raw e-commerce data into meaningful business metrics and an interactive dashboard.  
It follows the Medallion Architecture (Bronze → Silver → Gold) to ensure data quality, scalability, and clarity.

---

## Tech Stack

- Databricks
- Apache Spark (PySpark)
- Delta Lake
- Pandas
- Plotly
- Unity Catalog Volumes

---

## Data Pipeline Architecture

Raw CSV Files → Bronze → Silver → Gold → Dashboard

- Bronze: Raw data stored as Delta tables
- Silver: Cleaned and validated data
- Gold: Business-ready aggregated tables
- Dashboard: KPIs and charts built using Pandas and Plotly

---

## Key Gold Tables

- customer_order_summary
- daily_sales
- product_sales

These tables are used directly for reporting and dashboarding.

---

## Business KPIs

- Total Revenue
- Total Orders
- Total Customers
- Average Order Value (AOV)
- Purchase Frequency
- Customer Lifetime Value (CLV)
- Retention Rate

---

## Dashboard

The interactive dashboard includes:

- KPI cards for business metrics
- Sales trend over time
- Top selling products
- Revenue by customer region
- Customer retention analysis

---

## Why This Project Is Important

This project shows how raw data can be converted into business insights using real industry tools and architecture.  
It reflects how modern data teams build scalable analytics platforms.

---

## Author

Manu Yadav
