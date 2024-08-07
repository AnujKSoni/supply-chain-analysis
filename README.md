# supply-chain-analysis


Project Overview
This project focuses on the analysis of a supply chain dataset using Python for exploratory data analysis (EDA) and Power BI for visualization and dashboard creation. The dataset contains information about three product types: Haircare, Cosmetics, and Skincare. The primary goal is to derive insights from the data and visualize key performance indicators (KPIs) to help understand the supply chain dynamics.

Dataset Description
The dataset includes the following columns:

Product type: The type of product (Haircare, Cosmetics, Skincare)
SKU: Stock Keeping Unit, a unique identifier for each product
Price: The price of the product
Availability: The availability status of the product
Number of products sold: The number of units sold
Revenue generated: The total revenue generated from sales
Customer demographics: Information about the customers
Stock levels: The current stock levels for different products
Lead times: The time taken from order to delivery
Order quantities: The quantities ordered
Shipping times: The time taken for shipping
Shipping carriers: The carriers used for shipping
Shipping costs: The cost of shipping
Supplier name: The name of the supplier
Location: The location of the supplier
Lead time: The lead time from the supplier
Production volumes: The volume of production
Manufacturing lead time: The time taken for manufacturing
Manufacturing costs: The costs involved in manufacturing
Inspection results: The results of product inspections
Defect rates: The percentage of defective products
Transportation modes: The modes of transportation used
Routes: The routes taken for transportation
Costs: The overall costs involved
Key Performance Indicators (KPIs)
The following KPIs were created for the Power BI dashboard:

Revenue Generated: Total revenue by product type or SKU.
Number of Products Sold: Sales volume by product type or SKU.
Stock Levels: Current stock levels for different product types.
Lead Times: Average lead time from order to delivery.
Defect Rates: Percentage of defective products by product type.
Shipping Costs: Total shipping costs by carrier or transportation mode.
Customer Demographics: Sales distribution across different customer demographics.
Project Components
1. Power BI Dashboard
The Power BI dashboard provides a comprehensive visualization of the KPIs, enabling stakeholders to understand the supply chain performance at a glance. The dashboard includes:

Interactive charts and graphs for revenue, sales volume, stock levels, lead times, defect rates, and shipping costs.
Filters and slicers to explore data by product type, SKU, and customer demographics.
Visualizations that help identify trends, patterns, and areas for improvement in the supply chain.
2. Python Script for Exploratory Data Analysis (EDA)
The Python script (eda.py) performs detailed exploratory data analysis on the supply chain dataset. The script includes:

Loading and preprocessing the dataset.
Performing one-hot encoding for categorical variables.
Calculating and visualizing the correlation matrix.
Generating summary statistics and visualizations for key variables.
Identifying patterns and insights to inform the creation of KPIs for the Power BI dashboard.
