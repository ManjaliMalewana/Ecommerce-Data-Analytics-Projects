# 🗄️ SQL Data Analysis | DecodeLabs Internship

# 📊 Project Overview

Used SQL (via SQLite) to query the cleaned dataset and extract
business intelligence — covering filtering, grouping, aggregation,
and ranking across 1,200 orders.

# 📁 Files in This Repository

FileDescription

SQL_ANALYSIS_REPORT.txt --> Full report with all queries & findings

Dataset_Cleaned_Project1.csv ---> Dataset cleaned in Project1

Project3Workspace.ipynb ---> Notebook with 12 SQL queries + results

sql_revenue_by_product.png ---> Revenue by product chart

sql_monthly_trend.png ---> Monthly orders/revenue trend chart

# 🎯 Goal

Use SQL queries to extract insights from a dataset using SELECT,
WHERE, GROUP BY, ORDER BY, and aggregate functions.

# 🔧 SQL Techniques Demonstrated

View raw data    SELECT *, LIMIT

Count metrics    COUNT(), DISTINCT

Revenue stats    SUM(), AVG(), MIN(), MAX(), ROUND()

High-value orders  WHERE, ORDER BY DESC

Revenue by product  GROUP BY

Payment method %  Subquery for percentage

Top 10 orders    ORDER BY, LIMIT

Filtered + grouped  WHERE + GROUP BY combined

High-volume products   HAVING

Monthly trends      SUBSTR() for date grouping

# 💡 Key Business Insights


Identified top-performing product by revenue
Found dominant payment method and customer preference
Determined most effective marketing/referral channel
Built monthly trend view for seasonal planning
Used HAVING to isolate high-volume, stock-critical products


# 🛠️ Tools Used

Python, SQLite, Pandas, Matplotlib, Google Colab

# 📚 Key Learnings


SQL's logical execution order (FROM → WHERE → GROUP BY →
HAVING → SELECT → ORDER BY) differs from how it's written

Difference between WHERE (row-level filter) and HAVING
(group-level filter)

Writing subqueries for percentage calculations

Translating SQL output into an executive summary
