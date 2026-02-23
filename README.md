# Food Delivery Sales Analysis (ShopeeFood)

## Overview

This project analyzes sales performance of a small food business operating through the ShopeeFood platform.

The goal is to understand revenue trends, platform costs, and operational performance to support better business decisions.

Period: November 2025 – January 2026
Tools: Google Sheets / Microsoft Excel

---

## Objectives

* Measure monthly revenue performance
* Understand the impact of platform fees
* Identify peak sales hours
* Track business trends over time

---

## Dataset

Data was exported from the ShopeeFood Partner dashboard.

Characteristics:

* One row represents one order transaction
* Includes gross amount, commission, subsidy, and net revenue
* Covers three months of operations

---

## Project Structure

The project is organized into three main parts:

### Raw Data

* `staging_sales`
* `dim_store`

Contains cleaned transactional data from the source system.

### Analysis

* Monthly pivot tables
* Hourly analysis
* KPI calculations

Used to transform raw data into meaningful metrics.

### Dashboard

* KPI summary
* Monthly trends
* Sales distribution by hour

Provides a visual overview of business performance.

---

## Data Preparation

Main steps:

* Standardizing date and time formats
* Extracting month and hour features
* Validating numeric fields
* Building pivot tables for analysis

---

## Key Metrics

* Total Orders
* Gross Sales
* Net Revenue
* Platform Fee Ratio
* Average Order Value
* Monthly Growth

---

## Key Insights

* Platform fees account for a significant portion of revenue.
* Sales activity is concentrated around lunch hours.
* Monthly performance varies depending on promotional intensity.

---

## Tools Used

* Google Sheets / Microsoft Excel
* Pivot Tables
* Data Cleaning Functions
* Basic Visualization

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

## Author

This project was created as part of personal learning and portfolio development using a real business case.
