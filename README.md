# Global Superstore Sales Analysis Dashboard (Power BI)
## Project Overview

This project presents an interactive Power BI dashboard built using the Global Superstore dataset.
The goal is to analyze sales performance, profit trends, customer distribution, and regional insights to support data-driven business decisions.

The dashboard is designed with a professional data model, clean visuals, and interactive filters for deeper exploration.

## Objectives

Analyze sales and profit performance across regions and countries

Identify top-performing products and categories

Visualize geographical sales distribution using maps

Enable interactive analysis using slicers and drill-downs

Apply best practices in Power BI modeling and visualization

## Dataset

Dataset Name: Global Superstore
Data Type: Retail Sales Data

Key Columns:

Order Date

Region, Country, State, City

Category, Sub-Category, Product Name

Sales, Profit, Quantity

Segment, Customer Name

## Tools & Technologies

Power BI Desktop

Power Query (Data Cleaning & Transformation)

DAX (Measures & KPIs)

Excel (Source Dataset)

## Dashboard Features

Sales & Profit KPIs

Geographical Map Visualization (Country / State level)

Category & Sub-Category Analysis

Trend Analysis (Time Series)

Top N Products by Sales

Interactive Filters & Slicers

## Data Model

Fact Table: Orders

Dimension Tables:

Location (Country, State, City)

Product

Date

Relationships are designed using a star schema to improve performance and accuracy.

## Key Measures (DAX)
Total Sales = SUM(Orders[Sales])

Total Profit = SUM(Orders[Profit])

Total Quantity = SUM(Orders[Quantity])

Profit Margin = DIVIDE([Total Profit], [Total Sales])

## How to Use

Download the .pbix file from this repository

Open it using Power BI Desktop

Refresh data (if required)

Use slicers to explore insights by:

Region

Category

Segment

Time period

## Business Insights

Identifies high-revenue regions and markets

Highlights loss-making products

Helps understand customer purchasing behavior

Supports strategic decision-making

## Repository Structure

### Global-Superstore-PowerBI
│── 📄 Global Superstore Sales Analysis Dashboard.pbix

│── 📄 README.md

## Future Enhancements

Add forecasting using time-series analysis

Include advanced DAX measures

Optimize performance for large datasets

Publish dashboard to Power BI Service

## Author

Muhammed Nihal
