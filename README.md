# Mobile Sales Dashboard (Power BI)

This project presents an interactive Power BI dashboard designed to analyze mobile sales data and generate business insights. The dashboard provides a clear view of sales performance across different cities, brands, payment methods, and time periods.

## Project Overview

The objective of this project is to build a sales analytics dashboard that helps understand mobile product performance and customer purchasing patterns. Using Power BI, the dataset was transformed and visualized to create meaningful insights through interactive charts and KPIs.

## Tools & Technologies Used

- Microsoft Power BI
- Power Query (Data Cleaning & Transformation)
- DAX (Data Analysis Expressions)
- Microsoft Excel (Dataset)

## Data Preparation

The dataset was imported from Excel and processed using Power Query. Data transformation steps included cleaning the dataset, formatting columns, and preparing date fields for time-based analysis.

## DAX Measures

DAX formulas were used to calculate important business metrics.

Example measure used:

Total Sales = SUMX(Sales_Data, Sales_Data[Units Sold] * Sales_Data[Price Per Unit])

Other KPIs created in the dashboard include:

- Total Sales
- Total Quantity
- Transactions
- Average Sales

## Dashboard Features

The Power BI dashboard includes multiple interactive visualizations:

- KPI Cards displaying Total Sales, Quantity, Transactions, and Average Sales
- Map visualization showing Total Sales by City
- Line charts analyzing Quantity and Sales trends
- Bar chart showing Total Sales by Mobile Model
- Pie chart displaying Payment Method distribution
- Funnel chart visualizing Customer Ratings
- Table summarizing Brand-wise sales performance

Interactive slicers allow users to filter the dashboard by:

- Month
- Mobile Model
- Payment Method
- Brand
- Day Name

## Dashboard Preview

![Dashboard](dashboard.png)

## Key Insights

- Sales distribution varies across different cities.
- Certain mobile models generate higher sales compared to others.
- Payment method usage shows customer preference patterns.
- Sales trends vary across different days and months.

## Project Files

This repository contains:

- Sales_Dashboard.pbix – Power BI dashboard file
- Mobile Sales Data.xlsx – Dataset used for analysis
- dashboard.png – Dashboard screenshot
- README.md – Project documentation

## Author

Atharva Babhulgaonkar
