# AdventureWorks Project

🚴‍♂️ AdventureWorks: Cycles Sales & Operations Analytics Dashboard

A comprehensive and interactive Power BI reporting solution designed to analyze sales performance, product trends, customer behavior, and regional growth for AdventureWorks — a global manufacturer of bicycles and cycling accessories.


📌 1. Short Description / Purpose

The AdventureWorks Cycles Sales & Operations Dashboard transforms raw transactional data into actionable insights through four interactive Power BI dashboards: Executive, Map, Product, and Customer.
It helps business leaders track KPIs, understand regional sales trends, identify top-performing products, and discover high-value customers to support data-driven decision-making.


🛠️ 2. Tech Stack

The project was developed using the following tools and technologies:

📊 Power BI Desktop – Core platform for analytics and interactive dashboard creation

📂 Power Query / M Language – Data ingestion, transformation, and ETL automation

🧠 DAX (Data Analysis Expressions) – Advanced calculations, KPIs, and dynamic measures

🗄️ Data Modeling (Star Schema) – Fact/dimension modeling with optimized relationships

📁 File Formats – .pbix for development, .png for dashboard preview/exports


📚 3. Data Source

Source: Microsoft SQL Server – AdventureWorksDW (Sample Data Warehouse)

The dataset includes multiple tables representing sales, customers, products, territories, and internet transactions. Core tables used:

FactInternetSales – Sales transactions

DimCustomer – Customer profiles

DimProduct / DimProductSubcategory / DimProductCategory – Product hierarchy

DimGeography – Region and location data

DimDate – Calendar dimension used for time intelligence

This data models a real manufacturing environment, enabling reliable business analysis.


🌟 4. Features / Highlights

• Business Problem

AdventureWorks lacked a unified, interactive reporting system to monitor its sales, product performance, regional operations, and customer segments.
Leadership needed a comprehensive BI solution to answer questions such as:

Which regions and customer groups are driving the most revenue?

What product categories are under- or over-performing?

Who are the top customers and how often do they purchase?

How are KPIs trending compared to previous periods?

• Goal of the Dashboard

The dashboard suite was built to:

Provide executives a single source of truth for KPIs

Enable regional managers to compare territory-level sales performance

Help product teams analyze category and model-level trends

Support customer teams in identifying high-value customers and buying behavior

Deliver a clean, intuitive, and interactive experience for stakeholders at all levels


🧭 5. Walkthrough of Key Dashboards
1️⃣ Executive Dashboard

A high-level overview for leadership, featuring:

Total Revenue, Total Orders, Profit, YoY & MoM KPIs

Sales Trends (line charts)

Top Performing Products & Categories

Overall business health indicators

2️⃣ Map Dashboard

Focused on geography and regional dynamics:

Sales by Country/State using filled maps

Regional growth indicators & YoY comparison

Territory-level customer contributions

Interactive map slicers & drill-through navigation

3️⃣ Product Detail Dashboard

Deep-dive analysis for product strategists:

Revenue by Category, Subcategory, and Model

Top-selling products with dynamic filters

Price segment analysis vs. sales volume

Trend charts for product demand & seasonal patterns

4️⃣ Customer Detail Dashboard

Designed for customer analytics:

Customer segmentation by revenue, region, and frequency

High-value customer identification

Purchase behavior trends

Customer lifetime value (CLV) insights

Dynamic tables with conditional formatting


💡 Business Impact & Insights

Strategic Decision Support: Executives can quickly assess revenue trends and KPI performance.

Market Expansion: Region-level analysis highlights territories with growth potential.

Product Optimization: Identifies underperforming models and high-margin product opportunities.

Customer Retention: Helps teams target high-value buyers and understand purchasing cycles.

Operational Efficiency: Fully automated ETL flows and centralized reporting reduce manual effort.

🖼️ 6. Screenshots / Dashboard Previews

1️⃣ Executive Dashboard Preview
![Executive Dashboard](https://github.com/Shivam163Sharma/AdventureWorks-Report/blob/main/AdventureWorks%20Report%20Dashboard.png)

2️⃣ Map Dashboard Preview
![Map Dashboard](https://github.com/Shivam163Sharma/AdventureWorks-Report/blob/main/Map%20Dashboard.png)

3️⃣ Product Details Dashboard Preview
![Product Dashboard](https://github.com/Shivam163Sharma/AdventureWorks-Report/blob/main/Product%20Details%20Dashboard.png)

4️⃣ Customer Details Dashboard Preview
![Customer Dashboard](https://github.com/Shivam163Sharma/AdventureWorks-Report/blob/main/Customer%20Details%20Dashboard.png)

