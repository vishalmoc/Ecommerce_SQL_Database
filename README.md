# Ecommerce_SQL_Database
Ecommerce_SQL_Database
# 📊 SQL for Data Analysis – E-Commerce Dataset

This repository contains SQL queries and analysis performed as part of the **Data Analyst Internship at Elevate Labs (MSME, Govt. of India)**. The objective was to extract insights from an E-commerce database using SQL.

---

## 📌 Objective

Use SQL queries to extract, manipulate, and analyze structured data from a relational database.

---

## 🧰 Tools & Technologies

- **SQL Engine:** MySQL (can also work with PostgreSQL or SQLite)
- **Database:** E-commerce SQL Dataset
- **IDE:** MySQL Workbench / DB Browser / pgAdmin

---

## 📂 Dataset

**Ecommerce_SQL_Database**  
The dataset contains the following tables:

- `customers` – Customer profile information
- `orders` – Order transaction details
- `order_items` – Individual product items within orders
- `products` – Product catalog
- `payments` – Payment and billing info

---

## 📄 Files Included

- `sql_analysis_task.sql` – All SQL queries used in this project
- `screenshots/` – Screenshots of query outputs
- `README.md` – Project overview and explanation

---

## ✅ Task Checklist

- [x] Use `SELECT`, `WHERE`, `ORDER BY`, `GROUP BY`
- [x] Perform `JOINs`: `INNER`, `LEFT`, `RIGHT`
- [x] Use subqueries and aggregate functions (`SUM`, `AVG`)
- [x] Create views for analysis
- [x] Optimize queries with indexes
- [x] Handle `NULL` values appropriately

---

## 🔎 Sample SQL Queries

```sql
-- Average revenue per user
SELECT customer_id, AVG(total_amount) AS avg_revenue
FROM orders
GROUP BY customer_id;
