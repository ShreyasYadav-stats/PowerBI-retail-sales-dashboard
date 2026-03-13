# Retail Sales Dashboard (Power BI)

## Overview

This project demonstrates the design of an interactive Power BI dashboard for exploring retail sales performance across geography, time, product categories and customer demographics.

The purpose of this project is to showcase familiarity with Power BI as a business intelligence and data visualisation tool, including dashboard layout, KPI reporting and interactive filtering. This project focuses on visual reporting and dashboard construction rather than statistical modelling.

## Dashboard Preview

![Dashboard](images/dashboard_preview.png)

## Key Features

The dashboard provides a high level overview of retail sales performance and allows users to explore the data interactively.

Main components include:

- KPI Summary
  - Total Sales
  - Quantity Sold
  - Average Order Value

- Geographic Analysis
  - Store locations visualised using ArcGIS Maps for Power BI
  - Sales aggregated by Australian state
  - Interactive filtering between map and tables

- Time Series Analysis
  - Monthly trend of total sales and quantity sold

- Customer Segmentation
  - Sales distribution across age groups

- Product Performance
  - Revenue contribution by product category
  - Category performance by state

- Interactive Drill Down
  - Selecting a state filters store level sales data

## Tools and Technologies

This project uses:

- Power BI
- ArcGIS Maps for Power BI
- R for data enrichment and location generation
- Power Query for data preparation

## Data

The dataset used in this project is a synthetic retail sales dataset containing:

- transaction records
- product categories
- customer demographics
- sales amounts and quantities

Store locations were generated programmatically to simulate Australian retail outlets.

## Repository Structure

```text
powerbi-retail-sales-dashboard/
│
├── dashboard/
│   └── retail_sales_dashboard.pbix
├── data/
│   └── retail_sales_with_locations.csv
├── images/
│   └── dashboard_preview.png
└── scripts/
    └── generate_locations.R

## How to Use

1. Download the `.pbix` file from the **dashboard** folder.
2. Open it using **Power BI Desktop**.
3. Interact with the visuals by selecting states and exploring the linked charts and tables.

---

## Purpose of the Project

This project is intended as a **Power BI portfolio piece**, demonstrating:

- dashboard construction
- business KPI reporting
- interactive visual exploration
- integration of geospatial visuals

More advanced statistical analysis and modelling are demonstrated in other repositories.
