📌 Jenson USA Sales & Customer Analysis – SQL Project
📖 Overview

This project performs a detailed SQL-based analysis of Jenson USA, a retail company selling bikes and accessories.
Using multi-table relational data, the goal is to understand:

Store performance

Customer spending behavior

Staff efficiency

Product & category performance

Pricing insights

Inventory movement

Revenue trends

Advanced SQL techniques like joins, aggregations, subqueries, and window functions were used to uncover deep business insights.
---------------------------------------------------
📂 Dataset Information

The dataset consists of multiple relational tables:

Customers – customer details

Stores – store locations and IDs

Staff – employee details

Orders – orders made by customers

Order Items – product-level details of each order

Products – product catalog

Categories – product category information

This setup enables multi-dimensional analysis across customers, products, staff, and stores.
---------------------------------------
🔍 Key SQL Queries Performed

The analysis includes SQL queries to answer:

Total products sold by each store

Cumulative sales per product

Best-selling product in each category

Highest spending customer

Highest priced product per category

Order count per customer per store

Staff members with zero sales

Top 3 products by quantity sold

Median product price

Products that were never sold

Staff with above-average sales

Customers who purchased from ALL categories

👉 All SQL queries are included in the attached PDF file.
------------------------------------------------------------------
📊 INSIGHTS

🏬 1. Store Performance Insights

Significant difference between top-selling and low-selling stores.

Some stores consistently maintain high order volumes, indicating strong demand.

Low-performing stores may need marketing support, inventory adjustments, or location review.

👥 2. Customer Insights

A few customers are responsible for a large share of total revenue → high-value customers.

Many customers have placed orders across multiple stores → shows strong brand loyalty.

Customers with zero orders represent potential for targeted engagement campaigns.

📦 3. Product & Category Insights

Each category has a clear top-selling product, helping identify customer preferences.

Several products remain completely unsold, indicating:

Poor visibility

Irrelevant pricing

Low customer demand

Top three products by quantity reveal the most in-demand items.

💰 4. Pricing & Demand Insights

Highest-priced products differ significantly by category, highlighting premium vs budget segments.

Calculated median product price gives a balanced view of overall pricing.

Price vs sales comparison shows that:

Some low-cost items sell very well

Some high-priced items have niche demand

👨‍💼 5. Staff Performance Insights

Some staff members made zero sales, showing low productivity or training issues.

High-performing staff consistently exceed average sales and may be rewarded or benchmarked.

Staff performance directly impacts store-level revenue.

📈 6. Category-Wide Purchase Patterns

Identified customers who purchase across all categories, indicating:

High engagement

Strong interest in diverse products

Potential premium customer segment

🧮 7. Cumulative & Trend Insights

Cumulative sales per product show long-term demand patterns.

Helps identify:

Consistent sellers

Seasonal products

Products with rising or falling trends

🎯 Overall Insights Summary

The SQL analysis revealed:

Clear top and low-performing stores

Highly valuable customers for retention strategy

Unsold inventory needing clearance or promotion

Best-selling product categories

Underperforming staff who may need support

Premium-priced vs budget-focused product patterns

Categories with strong customer interest

A detailed picture of business performance across multiple dimensions

This analysis demonstrates how SQL can generate real, actionable business insights from raw retail data.
------------------------------------------
🛠️ SQL Concepts Used

INNER JOIN, LEFT JOIN

GROUP BY, HAVING

Aggregations: SUM, COUNT, AVG

Window Functions (RANK, ROW_NUMBER, SUM OVER)

Subqueries

DISTINCT

Median calculation

Conditional filtering

Sorting & ordering

🧰 Tools Used

MySQL

GitHub

PDF Documentation

Relational Database Concepts

📄 Files Included

Jenson USA SQL Project.pdf – Full queries + explanations
