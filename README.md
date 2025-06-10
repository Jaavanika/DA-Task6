# DA-Task6

# Sales Data SQL Analysis

This project contains SQL queries written to analyze and summarize business insights from a retail sales dataset.

##Dataset Overview

The dataset includes the following columns:

- `Transaction ID`
- `Date`
- `Product Category`
- `Product Name`
- `Units Sold`
- `Unit Price`
- `Total Revenue`
- `Region`
- `Payment Method`

---

##Part 1: Basic SQL Queries (SQLite Friendly)

These queries help explore and understand the data:

- Show all data  
- Select specific columns  
- Count total transactions  
- Calculate total revenue  
- List unique product categories  
- Filter by region or payment method  
- Get records with units sold > 10  
- View transactions from a specific month  

---

##Part 2: Business Insights Queries (MySQL / SQLite)

These queries extract meaningful business intelligence:

- Monthly revenue calculation  
- Revenue by product category  
- Top products by revenue  
- Transactions paid via credit card  
- Units sold in the last 6 months  
- Best-performing region by revenue  

The queries use:
- `SUM()` for revenue analysis  
- `COUNT(DISTINCT ...)` for transaction volume  
- `GROUP BY` for summarizing data  
- `ORDER BY` and `LIMIT` for sorting and top-N filtering  
- Date filtering using `strftime()` (SQLite) or `YEAR()/MONTH()` (MySQL)

