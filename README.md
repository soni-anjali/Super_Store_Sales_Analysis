# Superstores Sales Analysis

## Overview
This project is a **Superstores Sales Analysis** dashboard built using **Power BI**, **SQL**, and **Excel**. It provides insights into sales performance, profit trends, and a 15-day sales forecast using various interactive visualizations.

## Tools Used
- **Power BI**: For data visualization and dashboard creation
- **SQL**: For data extraction and transformation
- **Excel**: For data cleaning and preprocessing

## KPIs Tracked
- **Total Quantity Sold**
- **Total Sales**
- **Total Profit**

## Dashboard Features
### Page 1: Sales Analysis
- **Slicer**: Enables filtering by **Region**
- **Donut Charts**: Visualizes sales distribution
  - Sales by **Payment Mode**
  - Sales by **Segment**
  - Sales by **Region**
- **Stacked Area Chart**: Displays trends over time
  - **Sales by Month**
  - **Profit by Month**
- **Clustered Bar Chart**: Compares different sales metrics
  - Sales by **Category**
  - Sales by **Subcategory**
  - Sales by **Ship Mode**

### Page 2: Sales Forecast
- **Line Chart**: Forecasts **Superstore Sales** for the next **15 days**
- **Bar Chart**: Displays **Sales by Region**
- **DAX Query**: To Forecaste Sales **SalesForecast = SUMMARIZE('SuperStore_Sales_Dataset',SuperStore_Sales_Dataset[Order Date],"Total Sales",SUM(SuperStore_Sales_Dataset[Sales]))**

## How to Use
1. Open the Power BI dashboard file.
2. Use the slicer to filter data by region.
3. Analyze sales trends using interactive visuals.
4. Navigate to the second page for future sales predictions.

## Repository Contents
- **Dataset**: Raw and cleaned data files
- **Power BI File**: Contains the dashboard
- **SQL Scripts**: Queries used for data extraction
- **Excel File**: Data preprocessing sheets




