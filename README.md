# Data Analytics Journey 🚀

## About Me
- Name: Thulasi
- Background: B.Tech CSE, CGPA 9.0
- Goal: Data Analyst

## Skills I'm Building
- SQL
- Python
- Excel
- Power BI
- Tableau

## Projects
(Coming soon...)

## Day 1 ✅
- Set up VS Code and Jupyter
- Learned Excel Pivot Tables
- Started 90-day journey
# Day 2 - Excel Advanced Formulas

## What I Learned Today

### XLOOKUP
- Syntax: =XLOOKUP(lookup_value, lookup_array, return_array)
- Better than VLOOKUP because it works both directions
- Always wrap with IFERROR

### INDEX-MATCH
- MATCH finds the row number
- INDEX returns the value from that row
- Combined syntax: =INDEX(range, MATCH(value, range, 0))

### SUMIFS
- Sum with multiple conditions
- Syntax: =SUMIFS(sum_range, criteria_range, criteria)

## Challenges Solved
- [x] Multi-sheet lookup model
- [x] 5 practice challenges
- [x] AI-generated questions attempted

# Day 3 - Excel Dashboards + Power Query

## What I Built Today
- Sales Performance Dashboard with:
  - 3 KPI Cards (Revenue, Orders, AOV)
  - Bar Chart: Sales by Category
  - Line Chart: Monthly Sales Trend
  - Pie Chart: Sales by Region
  - Connected Slicers (Region + Category)

## Power Query Steps Learned
1. Load CSV data
2. Remove unnecessary columns
3. Change data types
4. Remove duplicates
5. Add calculated columns
6. Load clean data to Excel

# Day 4 - SQL Basics

## Concepts Learned
- SELECT, FROM, WHERE
- ORDER BY (ASC/DESC)
- GROUP BY
- Aggregate Functions (SUM/COUNT/AVG/MAX/MIN)
- HAVING vs WHERE difference
- DISTINCT
- LIMIT

## Key Rule I Learned Today
WHERE filters rows BEFORE grouping
HAVING filters groups AFTER grouping

## 10 Business Queries I Solved
1. Total sales per region 
2. Orders per category 
3. Average sales per segment
4. Most profitable region 
5. ...and so on

## HackerRank Score
Problems solved: 
□ Select All
□ Select By ID  
□ Japanese Cities Attributes
□ Japanese Cities Names
# Day 5 - SQL JOINs

## JOIN Types Summary

### INNER JOIN
- Returns only matching rows from both tables
- Use when: you want data that exists in BOTH tables
- Example: customers who placed orders

### LEFT JOIN  
- Returns ALL rows from left + matching from right
- NULL where no match in right table
- Use when: you want ALL records from main table
- Most powerful use: find records with NO match
- Example: customers who NEVER ordered

### RIGHT JOIN
- Opposite of LEFT JOIN
- Rarely used (rewrite as LEFT JOIN instead)

### FULL OUTER JOIN
- Returns everything from both tables
- MySQL: use UNION of LEFT + RIGHT JOIN

### SELF JOIN
- Table joins with itself
- Use for: hierarchical data, employee-manager

## The Golden Rule
LEFT JOIN + WHERE right_table.id IS NULL
= Find records with NO MATCH
This is asked in 90% of interviews

## 10 Business Queries Solved
1. Customer order details → INNER JOIN ✅
2. Customers who never ordered → LEFT JOIN ✅

...## Day 6 ✅
- Python functions for data analysis
- LinkedIn profile fully set up
- Connected with 20 analysts
- File handling in Python
