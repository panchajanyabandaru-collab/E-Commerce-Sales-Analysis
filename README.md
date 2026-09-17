E-Commerce Sales Analysis

E-commerce sales analysis project using Oracle SQL, Excel, and Power BI to analyze sales trends, profitability, customer behavior, product performance, and regional performance.

📌 Project Overview

This project analyzes 100 e-commerce transactions from January to March 2026. The workflow covers data preparation, SQL-based business analysis, Excel insights, and an interactive Power BI dashboard.

🎯 Objectives

Analyze revenue, cost, profit, and profit margin.

Identify monthly sales and profit trends.

Measure month-over-month sales growth.

Compare category, product, customer, and regional performance.

Identify top-performing products and customers.

Build an interactive dashboard for business reporting.

🛠️ Tools & Technologies

Oracle SQL Developer — Data analysis and business queries

Microsoft Excel — Data cleaning and business insights

Power BI — Dashboard and visualization

CSV — Source dataset

📊 Key Metrics

Metric

Value

Total Orders

100

Total Quantity

293

Total Sales

₹5,486,500

Total Cost

₹4,494,535

Total Profit

₹991,965

Profit Margin

18.08%

🔍 Key Insights

Monthly sales increased from ₹1.78M in January to ₹1.83M in February and ₹1.87M in March.

March recorded the highest monthly sales, while its profit margin was 15.45%, lower than January and February.

Electronics generated the highest sales at approximately ₹4.17M and the highest total profit at approximately ₹677K.

Laptop generated the highest total profit among the analyzed products.

Table had the highest quantity sold.

Meena generated the highest total sales and total profit among customers.

South generated the highest regional sales and profit.

Accessories recorded a relatively high profit margin of 28.13% despite having a smaller sales volume.

📈 Power BI Dashboard

The dashboard provides an interactive sales-performance overview with:

Total Revenue

Total Orders

Total Quantity

Average Order Value

Revenue by Category

Monthly Revenue Trend

Products by Revenue

Category, Region, and Month filters

Dashboard Preview



🧹 Data Preparation

The data workflow included:

Importing the CSV into an Oracle staging table.

Converting text fields into appropriate numeric and date data types.

Converting percentage values into numeric profit-margin values.

Standardizing category names.

Validating the imported row count.

Retaining Unknown where missing values had intentionally been replaced during data cleaning.

🧮 SQL Analysis

The final SQL script covers:

Overall business KPIs

Monthly sales and profit

Month-over-month sales growth using LAG()

Category performance

Product performance

Top 5 products by profit and quantity

Low-profit-margin products

Customer performance and profitability

Top 5 customers by sales, profit, and orders

Region and city performance

Payment-method performance

🗂️ Project Structure

E-Commerce-Sales-Analysis/
├── data/
│   └── ECOMMERCE_SALES.csv
├── sql/
│   └── ECOMMERCE_ANALYSIS_FINAL.sql
├── powerbi/
│   └── E-Commerce_Sales_Dashboard.pbix
├── excel/
│   └── Business_Insights.xlsx
├── screenshots/
│   └── dashboard.png
└── README.md

👨‍💻 Skills Demonstrated

SQL: Aggregations, GROUP BY, HAVING, ORDER BY, subqueries, ROWNUM, CASE expressions, date functions, and window functions.

Excel: Data cleaning, pivot-based analysis, business insights, and reporting.

Power BI: KPI cards, charts, slicers, filtering, dashboard layout, and business visualization.

📌 Conclusion

This project demonstrates an end-to-end data analytics workflow:

Data Preparation → SQL Analysis → Excel Insights → Power BI Dashboard → Business Interpretation
