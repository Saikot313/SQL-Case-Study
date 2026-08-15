# Advanced SQL Case Study

A practical SQL case study focused on advanced querying, data analysis, and business problem-solving using relational datasets.

## 📌 Project Overview

This project demonstrates the practical application of advanced SQL concepts through a series of analytical and business-oriented problems.

The case study covers SQL window functions, programming constructs, stored functions, stored procedures, query optimization, indexing, and real-world data analysis.

## 🎯 Objectives

- Apply advanced SQL concepts to real-world datasets
- Perform business-oriented data analysis using SQL
- Analyze customer, product, sales, and profitability data
- Practice advanced querying and window functions
- Implement stored functions and stored procedures
- Understand indexing and query optimization techniques
- Write clean, readable, and optimized SQL queries

## 🛠️ Technologies Used

- **SQL**
- **MySQL**
- **MySQL Workbench**
- **Relational Database**
- **IMDb / Business Dataset**

## 📚 Key SQL Concepts Covered

### 1. Window Functions

The project uses different window functions for ranking and analytical operations, including:

- `RANK()`
- `DENSE_RANK()`
- `PERCENT_RANK()`
- `ROW_NUMBER()`
- `LEAD()`
- `LAG()`
- Window Frames
- Named Windows

These functions are used to perform row-level analysis while retaining access to related rows within a result set.

### 2. Programming Constructs

The project demonstrates SQL programming constructs such as:

- `CASE` statements
- User-Defined Functions (UDFs)
- Stored Procedures
- Function vs Stored Procedure

### 3. Query Optimization

The project also focuses on writing efficient and maintainable SQL queries.

Topics include:

- SQL query execution order
- Query formatting
- Table aliases
- Descriptive naming
- Proper indentation
- SQL indexing
- Clustered and non-clustered indexes

## 📊 Business Analysis

The case study includes several practical business problems.

### Profitability Analysis

The analysis identifies sustainable and profitable product categories by examining:

- Total profit by product category
- Total profit by product subcategory
- Average profit per order
- Average profit percentage per order

### Profitable Customers

The project identifies the **top 10 most profitable customers** using customer and market transaction data.

The analysis includes:

- Customer ID
- Customer name
- Customer location
- Profit
- Sales
- Customer ranking

### Customers Without Orders

The project also identifies customers who have not placed any orders.

The analysis includes:

- Customer ID
- Customer name
- City
- State
- Customer segment
- Duplicate customer identification based on name and city

## 🗂️ Database Schema

The business analysis uses a relational schema containing tables such as:

- `market_fact_full`
- `prod_dimen`
- `orders_dimen`
- `cust_dimen`
- `shipping_dimen`

The central `market_fact_full` table is connected with product, customer, order, and shipping-related dimension tables.

## 📁 Project Structure

```text
Advanced-SQL-Case-Study/
│
├── Adv. SQL Actual Script.sql
├── Commented Workbench demonstration2.sql
├── IMDB question.sql
├── IMDB dataset import.sql
├── IMDb movies Data and ERD final.xlsx
├── Adv. SQL PPT final.pptx
└── README.md
