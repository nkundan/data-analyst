# data-analyst
Blinkit Sales Analytics Dashboard – Project Details
Project Title:

Blinkit Sales Analytics Dashboard using Power BI

Project Domain:

Data Analysis & Business Intelligence

1. Project Overview

The Blinkit Sales Analytics Dashboard is an end-to-end data visualization project developed to analyze sales performance across different outlets, item categories, fat content, outlet size, and regional tiers.
The goal of the project is to provide decision-makers with actionable insights through interactive charts, KPIs, and filters.

The dashboard enables stakeholders to understand overall sales distribution, outlet growth over the years, customer preferences, and item-level performance.

2. Objectives of the Project

To create an interactive dashboard for Blinkit’s sales dataset.

To help management track Total Sales, Average Sales, Average Rating, and Total Items.

To analyze the impact of item fat content on total revenue.

To compare performance across outlet sizes (Small, Medium, High).

To evaluate which item types contribute the most to the revenue.

To study outlet performance based on location and type.

To visualize sales trends over time (2010–2022).

3. Dataset Description

The dataset contains information about:

Field	Description
Item Type	Category of item (Snacks, Fruits, Dairy, Meat, etc.)
Item Fat Content	Low Fat, Regular
Item Rating	Avg customer rating
Item Sales	Total revenue from item
Outlet Size	Small, Medium, High
Outlet Location	Tier I, Tier II, Tier III
Outlet Establishment Year	Year in which the outlet was opened
Outlet Type	Grocery Store & Supermarket Types
Number of Items	Total items sold in each outlet
4. Tools & Technologies Used

Power BI Desktop – Data Modeling, Visualization, DAX

Excel / CSV – Data Pre-processing

Power Query – Data Cleaning & Transformation

DAX Measures – Custom calculations for KPIs

5. Data Cleaning & Transformation

Performed using Power Query:

Removed duplicates and null values

Standardized categories (e.g., "LF" → "Low Fat")

Created new calculated columns for item visibility, outlet age, etc.

Converted text to correct data types (numeric, date, categorical)

6. Measures Created (DAX)

Sample measures used:

Total Sales = SUM(Item_Outlet_Sales)

Avg Sales = AVERAGE(Item_Outlet_Sales)

Total Items = COUNT(Item_Identifier)

Outlet Age = YEAR(TODAY()) – [Outlet Establishment Year]

Fat Content Sales = CALCULATE(SUM(Item_Outlet_Sales), FILTER(...))

7. Key Dashboard Features
✔ KPI Cards

$1.20M – Total Sales

$141 – Avg Sales

4 – Average Rating

8523 – No. of Items

✔ Sales Trend (Outlet Establishment)

Line graph showing growth from 2010 to 2022

Peak sales around $205K in 2018

✔ Item Fat Content Analysis

Donut chart comparing Low Fat vs Regular

Revenue distribution:

Low Fat → $425.36K

Regular → $776.63K

✔ Outlet Size Analysis

Medium-sized stores lead with $507.90K sales

✔ Outlet Location Tier Analysis

Tier 3 performs highest with $472.13K

✔ Item Type Breakdown

Highest sales categories:

Fruits – $178K

Snacks – $175K

Household – $136K

✔ Outlet Type Comparison

Supermarket Type 1 leads with $787.55K total sales

8. Insights Generated
Business Insights

Regular fat items generate higher revenue than low-fat items.

Tier 3 outlets contribute the most to sales performance.

Medium-sized outlets perform better than small or large outlets.

Fruits & snacks are top-selling item categories.

Supermarket Type 1 outlets dominate in total sales and number of items.

A spike in sales occurred between 2017–2018 followed by a decline.

Grocery stores have fewer items but consistent average sales.

9. Challenges Faced

Resolving inconsistent fat-content labels (LF, low fat, reg, regular).

Cleaning item visibility values.

Handling missing outlet establishment year data.

Creating dynamic DAX measures for filter-based analysis.

10. Conclusion

The Blinkit Sales Analytics Dashboard successfully provides a comprehensive and intuitive visualization of the company’s sales performance. It helps management identify top-performing outlets, compare item categories, monitor long-term sales trends, and make data-driven decisions about inventory, promotions, and outlet placement.
