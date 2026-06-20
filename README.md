Ecommerce SQL Data Analysis

Project Overview

This project demonstrates SQL-based data analysis using an Ecommerce database in PostgreSQL. The objective is to extract meaningful insights from structured data using SQL queries and database concepts such as joins, aggregate functions, subqueries, views, and indexes.

Objectives

- Perform data retrieval using SQL queries
- Filter and sort data using WHERE and ORDER BY
- Analyze data using aggregate functions
- Combine data from multiple tables using JOINs
- Implement subqueries for advanced filtering
- Create views for reusable analysis
- Improve query performance using indexes

Tools Used

- PostgreSQL
- pgAdmin 4
- GitHub

Database Structure

Customers Table

Contains customer details such as name, email, city, country, and join date.

Products Table

Contains product information including category, price, and stock quantity.

Orders Table

Contains order transactions, quantities, total amount, and order status.

SQL Operations Performed

1. SELECT and WHERE

Retrieved customer records based on specific conditions.

2. ORDER BY

Sorted product data based on price in descending order.

3. GROUP BY and SUM

Calculated total sales based on order status.

4. AVG

Computed the average order value.

5. INNER JOIN

Combined customer, product, and order information.

6. LEFT JOIN

Retrieved all customers along with available order details.

7. Subquery

Identified products priced above the average product price.

8. View Creation

Created a reusable view named "sales_view" for sales analysis.

9. Index Creation

Created an index on the Orders table to improve query performance.

Files Included

- ecommerce.sql
- Dataset SQL Script
- Query Output Screenshots
- README.md

Learning Outcomes

Through this project, I gained practical experience in:

- SQL query writing
- Data filtering and sorting
- Aggregate functions
- Table joins
- Subqueries
- Views
- Indexes
- Database analysis using PostgreSQL

Conclusion

This project enhanced my understanding of SQL for data analysis and provided hands-on experience in working with relational databases using PostgreSQL and pgAdmin.
