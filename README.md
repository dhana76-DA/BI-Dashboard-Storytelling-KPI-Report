Global Superstore Sales Analysis (Power BI)

Project Overview
This project provides a comprehensive analysis of the Global Superstore dataset. The goal was to transform raw sales data into an interactive dashboard that allows stakeholders to track key performance indicators (KPIs), identify regional trends, and analyze product-level performance.

Tools Used
Excel: Used for initial data exploration and source file management.
Power BI Desktop: The primary tool for data modeling, visualization, and dashboard creation.
DAX (Data Analysis Expressions): Used to create custom calculated measures for KPIs.
Git/GitHub: Used for version control and project documentation.

Data Architecture & Workflow
The project followed a standard Business Intelligence workflow:
Data Connection: Imported the Excel dataset into Power BI.
Data Transformation: Utilized Power Query to ensure correct data types (Dates, Currency, etc.) and cleaned any null values.
DAX Calculations: Developed measures for:
Total Sales: SUM(Sales[Amount])
Total Profit: SUM(Sales[Profit])
Profit Margin: DIVIDE([Total Profit], [Total Sales], 0)

Data Visualization: Designed a user-centric dashboard with high-level summaries and granular drill-down options.

Dashboard Features
The final dashboard includes:

Executive Summary: KPI cards highlighting Sales, Profit, and Margin at the top for immediate impact.
Trend Analysis: A line chart showing Sales performance over time to identify seasonality.
Categorical Breakdown: Bar charts to compare performance across different product categories.
Geographic Performance: A regional map/bar chart to pinpoint high and low-performing markets.

Product Deep-Dive: A "Top 10 Products" table to highlight revenue drivers.
Interactive Slicers: Dynamic filters for Region, Date, and Category to allow for self-service analysis.
