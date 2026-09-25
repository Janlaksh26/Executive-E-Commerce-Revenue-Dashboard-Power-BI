## Executive E-Commerce & Revenue Dashboard | Power BI

##  Project Overview

The Executive E-Commerce & Revenue Dashboard is an interactive Power BI business intelligence project developed to analyze e-commerce sales performance, profitability, customer behavior, regional performance, delivery efficiency, and payment trends.

The dashboard transforms transactional sales data into interactive visual reports that help users monitor key business performance indicators and identify important sales patterns.

## Project Objectives

* Analyze overall sales and profitability.
* Monitor total revenue, profit, orders, and delivery performance.
* Compare sales performance across regions and categories.
* Analyze customer-level sales and profitability.
* Understand customer segment performance.
* Analyze payment-mode distribution.
* Evaluate state-level delivery performance.
* Identify historical sales trends.
* Forecast future sales based on historical trends.

##  Tools & Technologies

* **Power BI**
* **Power Query**
* **DAX**
* **Data Visualization**
* **Business Intelligence**
* **Data Analysis**

##  Dataset
This Dataset was imported from Kaggle 
The dataset contains transactional e-commerce sales information, including:

* Order ID
* Order Date
* Customer Name
* State
* Region
* Category
* Segment
* Sales
* Profit
* Delivery Days
* Payment Mode

##  Project Workflow

1. Data Preparation

Imported the transactional sales dataset into Power BI and reviewed the structure, data types, and fields required for analysis.

2. Data Transformation

Used Power Query to prepare and transform the data for analysis.

3. Data Analysis

Created DAX measures to calculate important business KPIs such as revenue, profit, order volume, and average delivery time.

4. Dashboard Development

Designed an interactive dashboard containing KPI cards, slicers, charts, tables, and customer analysis visuals.

5. Forecasting

Applied Power BI's forecasting functionality to historical sales trends to estimate future sales and visualize the associated confidence interval.


## Dashboard Analysis

1.Sales Trend Analysis

A time-series visualization is used to analyze sales performance over the selected period and identify historical trends.

2.Regional & Category Analysis

Sales are compared across different regions and product categories to understand variations in business performance.

3.Customer Analysis

Customer-level sales, profit, and order volume are analyzed to identify differences in customer contribution.

4.Segment Analysis

Sales distribution across customer segments is visualized to understand segment-level contribution.

5.Delivery Analysis

Average delivery days are analyzed at the state level to identify geographical differences in delivery performance.

6.Payment Mode Analysis

Sales distribution across payment modes is analyzed to understand customer payment preferences.

## Interactive Features

The dashboard includes interactive slicers for:

1.Region
2.Category

These filters dynamically update the dashboard visuals and KPI values based on the selected criteria.

##  Visualizations Used

* KPI Cards
* Line Chart
* Bar Chart
* Pie Chart
* Donut Chart
* Scatter Plot
* Table
* Slicers


##  DAX Measures

Example measures used in the dashboard include:


1.Total Sales = SUM(Sheet1[Sales])
2.Total Profit = SUM(Sheet1[Profit])
3.Total Orders = COUNT(Sheet1[Order ID])
4.Average Delivery Days = AVERAGE(Sheet1[Delivery Days])

These measures enable dynamic KPI calculations based on the current filter context.

## Business Insights

The dashboard enables users to:

* Monitor overall revenue and profitability.
* Compare regional sales performance.
* Identify category-level sales patterns.
* Analyze customer contribution to sales and profit.
* Compare customer segment performance.
* Evaluate geographical delivery performance.
* Understand payment-mode sales distribution.
* Analyze historical sales trends.
* Explore potential future sales trends through forecasting.


##  Skills Demonstrated

* Power BI Dashboard Development
* Power Query
* DAX
* Data Cleaning & Transformation
* Data Visualization
* KPI Development
* Sales Analysis
* Customer Analysis
* Interactive Reporting


⭐ If you found this project useful, feel free to explore the repository.

