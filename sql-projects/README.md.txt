 SQL Projects

End-to-end SQL analysis performed in MySQL
Workbench, demonstrating data exploration,
aggregation, joins, and advanced querying
techniques on real-world business data.



📊 Superstore SQL Analysis

File: superstore _ analysis _ complete.sql
Tool: MySQL Workbench
Dataset: Superstore Sales (9,994 rows)

 Overview
A complete SQL analysis of retail sales data
spanning 2014–2017, covering revenue, profit,
regional performance, and customer behavior.

Business Questions Answered
1. What is the overall revenue, profit and
   profit margin?
2. Which region generates the most sales
   and profit?
3. Which product category is most profitable?
4. Who are the top 5 customers by total spend?
5. Which states generate the most orders?
6. What is the monthly sales trend?

Techniques Used
- Aggregate functions (`SUM`, `AVG`, `COUNT`)
- `GROUP BY` and `HAVING`
- CTEs for sub-category performance
- Window functions (`RANK() OVER (PARTITION BY ...)`)
  to rank customers within each region
- Subqueries to find above-average sales
- Loss-making product identification

 Key Findings
- Total Revenue: $2,272,449.86
- Profit Margin: 12.6%
- West Region leads in total sales
- The technology category has the highest
  profit margin
- Identified specific loss-making products
  in the Furniture category



How to Run

1. Import `Sample-Superstore.csv` into
   MySQL Workbench using the Table Data
   Import Wizard
2. Open`superstore_analysis_complete.sql`
3. Run each query section individually
   to reproduce results



 Skills Demonstrated

Aggregations · Joins · CTEs · Window Functions ·
Subqueries · Data Cleaning in SQL