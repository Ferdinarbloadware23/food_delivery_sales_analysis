
# Food Delivery Sales Analysis ShopeeFood

## Project Overview

This project analyzes sales performance of a small food business operating through the ShopeeFood platform.

The objective is to understand revenue trends, platform costs, and operational performance in order to support better business decision-making.

Analysis period: November 2025 – January 2026
Tools: Google Sheets / Microsoft Excel

---

## Objectives

The analysis aims to answer the following questions:

* How much revenue is generated each month?
* What is the impact of platform fees on net revenue?
* What are the peak sales hours?
* How does business performance change over time?
* How efficient are promotions and platform costs?

---

## Dataset

Data was exported from the ShopeeFood Partner dashboard.

Dataset characteristics:

* One row represents one order transaction
* Includes gross amount, commission, subsidy, and net revenue
* Covers the period from November 2025 to January 2026

---

## Data Architecture

The project uses a layered structure to organize the data.

### Layer 1 — Raw / Staging Tables

* staging_sales
* dim_store

These tables contain cleaned transactional data from the source system.

### Layer 2 — Aggregated Tables

* fact_sales_monthly

This table summarizes performance at the monthly level.

### Layer 3 — Reporting

* Dashboard
* Insight notes

The structure is designed to be easily migrated to a SQL database in the future.

---

## Data Cleaning and Preparation

Key preparation steps include:

* Standardizing date and time formats
* Extracting derived features such as month and hour
* Validating numeric fields
* Handling missing values
* Building aggregated monthly metrics

---

## Key Metrics

Main metrics analyzed in this project:

* Total Orders
* Gross Sales
* Net Revenue
* Platform Fee Ratio
* Average Order Value
* Monthly Growth

---

## Dashboard

The dashboard presents business performance through:

* Gross versus Net Revenue comparison
* Monthly sales trends
* Sales distribution by hour
* Key performance indicators

Dashboard screenshots are available in the images folder.

---

## Key Insights

Some important findings from the analysis include:

* Platform fees represent a significant portion of total revenue.
* Sales activity is concentrated around specific peak hours.
* Monthly performance varies depending on promotional strategies.
* Net revenue growth does not always follow gross sales trends.

---

## Business Recommendations

Based on the analysis:

* Optimize operations during peak sales hours.
* Evaluate promotion strategies to maintain healthy margins.
* Monitor platform fees relative to revenue.
* Identify opportunities to increase average order value.

---

## Tools Used

* Google Sheets / Microsoft Excel
* Pivot Tables
* Data Cleaning Functions
* Data Visualization

---

## Repository Structure

```
project-folder/

data/
    sample_sales.csv

excel/
    Food_Delivery_Sales_Analysis.xlsx

images/
    dashboard.png

README.md
```

---

## Future Improvements

Possible future enhancements include:

* Integration with SQL database
* Multi-platform analysis (GrabFood and GoFood)
* Financial and cashflow analysis
* Interactive dashboards using BI tools

---
