# Sales-Analytics-Dashboard
Sales Analytics Dashboard Using Power Bi 
**📊 Project Overview**
This repository hosts the Power BI Desktop file (sALES_ANALYTICS_dashboard.pbix) for a comprehensive Sales Analytics Dashboard. The goal of this project is to transform raw sales data into actionable business intelligence, providing key stakeholders with a real-time view of sales performance, trends, and opportunities for optimization.
This dashboard serves as a single source of truth for measuring key performance indicators (KPIs) related to sales effectiveness and revenue generation.
**🎯 Goals and Objectives**
_The primary objectives of this dashboard are to:_
Monitor Performance: Provide real-time tracking of critical sales KPIs (e.g., Total Revenue, Profit Margin, Sales Volume).
Identify Trends: Visualize sales performance over time, allowing users to spot seasonal variations, growth trajectories, and anomalies.
Segment Analysis: Enable deep-dive analysis by key dimensions such as Region, Product Category, Sales Rep, and Customer Type.
Improve Forecasting: Offer historical data and trend lines to support more accurate sales forecasting and resource planning.
**🛠️ Technical Details**
1. Data Sources
The dashboard integrates data from the following source systems (replace these with your actual sources):
Sales Transactions: ERP/CRM System (e.g., SQL Server, Azure Database)
Product Master: Inventory Management System (e.g., Excel/SharePoint List)
Calendar/Date Table: Automatically generated or based on a standard dimension table.
2. Data Transformation (Power Query / M Language)
All data preparation, cleaning, and shaping were performed using Power Query within Power BI. Key transformations include:
Cleaning & Normalization: Handling null values, correcting data types, and standardizing text casing.
Date Dimension Creation: Ensuring a complete date table is available for time intelligence calculations.
Merge & Append: Combining sales facts with dimension tables (Products, Customers) to create a unified star schema.
3. Data Model (DAX Calculations)
A robust data model was implemented following a Star Schema approach for optimal query performance. Key DAX measures created for analysis include:
[Top 5 Customers]
Ranks and aggregates sales data for the top customers.
**🖼️ Key Dashboard Features.**
The report is structured into several interactive pages to guide the user through different levels of analysis:
Executive Summary: High-level KPIs, year-over-year comparisons, and a trend line of Total Revenue.
Product Deep Dive: Analysis of sales by product category, sub-category, and individual product performance (e.g., highest revenue, lowest profit margin).
Geographic Performance: Interactive map visualizations showing sales performance by region and city, allowing users to drill down.
Customer Analysis: Segmentation of customers by revenue tier (e.g., Gold, Silver, Bronze) and analysis of customer acquisition trends.
**🚀 Usage and Interaction**
The dashboard is designed to be fully interactive:
Slicers: Utilize the slicers on the left-hand side (Date, Region, Sales Rep) to filter the entire report view.

Drill-Down: Visualizations (like bar charts and tables) support drill-down functionality to explore data hierarchy.

Tooltips: Hover over any data point to reveal detailed context-specific information.
