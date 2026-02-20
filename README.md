# Vendor_Projects_Large_Dataset
This project analyzes vendor sales and profitability data using SQL Server Query for data extraction and transformation and Python for exploratory data analysis (EDA) and visualization.

**Project Overview**

The goal of this analysis is to uncover business insights related to:

Revenue drivers

Profit optimization

Vendor performance

Inventory efficiency

Pricing strategy effectiveness

This project demonstrates end-to-end data analytics workflow from querying raw data to generating actionable business insights.

**Tools & Technologies Used**

SQL (SQL Server) – Data querying, filtering, aggregations

Python

Pandas – Data cleaning & manipulation

NumPy – Numerical operations

Matplotlib & Seaborn – Data visualization

Jupyter Notebook (VS Code) – Analysis environment

**Dataset Description**

The dataset contains vendor and product-level transactional summary data, including:

Vendor information (vendor number, vendor name, brand)

Product details (description, volume)

Pricing data (purchase price, actual selling price)

Sales & purchase quantities

Revenue metrics (total sales dollars, total purchase dollars)

Profit metrics (gross profit, profit margin)

Inventory metrics (stock turnover, sales-to-purchase ratio)

**Business Problems Addressed**

**1️ -  Identifying Top Profit-Generating Products**

Analyzed gross profit by product to determine high-performing SKUs.

Impact: Helps prioritize high-margin and high-profit products.

**2️ -  Vendor Performance Evaluation**

Evaluated vendors based on total gross profit and average profit margin.

Impact: Supports vendor negotiation and performance optimization.

**3️ - Inventory Inefficiency Detection**

Compared purchase quantity vs sales quantity to identify overstocked products.

Impact: Reduces capital blocked in slow-moving inventory.

**4️ - Pricing Strategy Analysis**

Analyzed relationship between sales volume and profit margin.

Impact: Identifies whether pricing is aggressive, optimal, or margin-leaking.

**5️ - Revenue Driver Identification**

Examined relationship between total sales quantity and total sales dollars.

Key Finding: Revenue is primarily volume-driven.

Impact: Business growth depends heavily on increasing sales quantity of key products.

**Key Insights**

Strong positive relationship between sales quantity and total revenue.

Gross profit highly correlated with total sales dollars.

High-margin products often have lower sales volume.

Revenue is concentrated among a limited number of high-performing products.

Some inventory inefficiencies exist due to unsold stock.

**Visualizations Included**

Correlation Heatmap

Top Products by Gross Profit (Bar Chart)

Vendor Performance Comparison

Sales Quantity vs Profit Margin (Scatter Plot)

Sales Quantity vs Sales Revenue (Scatter Plot)

Overstocked Product Analysis

**Project Workflow**

Extract and filter data using SQL queries

Load dataset into Python using Pandas

Perform data cleaning and preprocessing

Conduct exploratory data analysis (EDA)

Build business-focused visualizations

Derive actionable insights

**Business Value**

This project demonstrates the ability to:

Translate raw data into business insights

Perform KPI-driven analysis

Detect inefficiencies and optimization opportunities

Communicate findings through clear visual storytelling

**Skills Demonstrated**

SQL querying & aggregation

Data cleaning and transformation

Exploratory Data Analysis (EDA)

Correlation and trend analysis

Business interpretation of data

Data visualization best practices
