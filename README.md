📊 Sales Performance & Profitability Analysis — Power BI
📌 Project Overview

This project delivers an end-to-end Power BI business intelligence solution analyzing sales performance, profitability drivers, discount impact, and regional operations.
The dashboard is designed to help stakeholders identify growth opportunities, loss-making products, pricing inefficiencies, and operational risks.

🎯 Business Objectives

Analyze overall sales and profit performance

Track year-over-year (YoY) trends

Identify loss drivers at category, sub-category, and product level

Measure discount impact on profitability

Evaluate regional and operational efficiency

🗂 Dataset Information

Source: Superstore Sales Dataset
Records: ~10,000 rows
Time Period: 2014 – 2017

Tables Used

Fact_Sales

Dim_Date

Dim_Product

Dim_Customer

Dim_Geography

Dim_ShipMode

🧱 Data Modeling

A Star Schema was implemented for optimal performance and scalability.

Central Fact_Sales table

Supporting dimension tables for slicing and filtering

Dedicated _Measures table for clean DAX organization

Time Intelligence enabled using a custom Dim_Date table

📷 See data model screenshot in the screenshots folder.

📐 Key KPIs

Total Sales

Total Profit

Profit Margin %

Sales YoY %

Average Discount

Loss Sales

📊 Dashboard Pages
1️⃣ Executive Overview

KPI cards with conditional formatting

Monthly Sales vs Last Year trend analysis

Category-wise Profit Margin comparison

High-level business summary with insights

📷 screenshots/01_executive_overview.png

2️⃣ Profitability Analysis

Profit decomposition tree to identify loss drivers

Category → Sub-category → Product drill-down

Conditional formatting for profit and margin

Identification of loss-heavy product segments

📷 screenshots/02_profitability_analysis.png

3️⃣ Discount & Product Impact

Scatter plot showing Discount vs Profit relationship

High discount risk and severe discount zones highlighted

Product-level table with profit margin and discount analysis

Top-selling but loss-making products identified

📷 screenshots/03_discount_product_impact.png

4️⃣ Geography & Operations

Map visualization of sales and profit by state

Profit Margin by Ship Mode comparison

Regional performance matrix

Identification of regions with high sales but weak margins

📷 screenshots/04_geography_operations.png

🔍 Key Business Insights

Sales declined 2.8% YoY, mainly driven by losses in the Furniture category

Technology category leads profitability despite lower discounting

Discounts above 40% show a strong correlation with negative profit margins

Certain regions generate strong revenue but suffer from operational inefficiencies

First Class shipping shows higher margins compared to Standard Class in some regions

🛠 Tools & Technologies

Power BI

DAX (Time Intelligence, Conditional Formatting, Measures)

Data Modeling (Star Schema)

Business Analysis

Data Visualization

📁 Repository Structure
Sales-Analysis-PowerBI/
├── dataset/
│   └── superstore_sales.csv
├── screenshots/
│   ├── 01_executive_overview.png
│   ├── 02_profitability_analysis.png
│   ├── 03_discount_product_impact.png
│   ├── 04_geography_operations.png
│   └── 05_data_model_schema.png
├── Sales_Analysis.pbix
└── README.md

💼 Project Context

This dashboard was developed as part of freelance analytics work, where raw datasets were transformed, modeled, and visualized to deliver actionable business insights for decision-makers.

🚀 How to Use

Download the Sales_Analysis.pbix file

Open in Power BI Desktop

Interact with slicers and visuals to explore insights

Review dataset and screenshots for reference

📌 Author

Rishab Malik
Power BI | SQL | Data Analytics

