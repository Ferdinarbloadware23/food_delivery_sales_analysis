# Food Delivery Sales Analysis (ShopeeFood)

## Overview

This project analyzes sales performance of a small food business operating through the ShopeeFood platform.

The objective is to understand revenue performance, platform cost impact, and customer ordering behavior to support better business decisions.

Period: November 2025 – January 2026  
Tools: Google Sheets / Microsoft Excel  

---

## Objectives

- Measure revenue performance across the observed period  
- Understand the impact of platform fees on net revenue  
- Identify peak ordering hours  
- Explore operational patterns from transaction data  

---

## Dataset

Data was exported from the ShopeeFood Partner dashboard.

Characteristics:

- One row represents one order transaction  
- Includes gross amount, commission fee, subsidy, and net revenue  
- Covers three months of operations  
- Duplicate transactions were removed during data cleaning  

---

## Project Structure

The project is organized into three main components:

### Raw Data

- staging_sales  
- dim_store  

Contains cleaned transactional data prepared for analysis.

### Analysis

- Monthly pivot tables  
- Hourly pivot tables  
- KPI calculations  

Used to transform raw data into meaningful business metrics.

### Dashboard

- KPI summary cards  
- Monthly revenue visualization  
- Order distribution by hour  

Provides a visual overview of business performance.

---

## Data Preparation

Main steps performed:

- Standardizing date and time formats  
- Extracting month and hour features  
- Validating numeric fields  
- Removing duplicate rows  
- Building pivot tables for analysis  

---

## Key Metrics

- Total Orders  
- Gross Revenue  
- Net Revenue  
- Platform Fee Ratio  
- Average Order Value (AOV)  

---

## Key Insights

- Revenue remained relatively stable across the three-month period, indicating consistent demand without strong growth or decline.  
- Platform fees account for around 45% of gross revenue, showing that commissions and promotional subsidies significantly impact profitability.  
- Order activity increases starting from 6 PM and peaks between 8 PM and 10 PM, confirming dinner time as the primary revenue driver.  
- Average order value is around Rp36K per transaction, which is typical for quick-service food categories and suggests potential for upselling or bundle strategies.  

---

## Tools Used

- Google Sheets / Microsoft Excel  
- Pivot Tables  
- Spreadsheet Functions  
- Basic Data Visualization  

---

## Repository Structure
project-folder/

data/
sample_sales.csv

excel/
food_delivery_sales_analysis.xlsx

images/
dashboard.png

README.md
