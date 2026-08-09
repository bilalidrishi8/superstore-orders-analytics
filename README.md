# 📊 Superstore Orders Analytics — SQL Project

![SQL](https://img.shields.io/badge/SQL-PostgreSQL-336791?style=for-the-badge\&logo=postgresql\&logoColor=white)
![Data Analysis](https://img.shields.io/badge/Data%20Analysis-SQL-orange?style=for-the-badge)
![GitHub](https://img.shields.io/badge/Project-GitHub-181717?style=for-the-badge\&logo=github)

## 📌 Project Overview

**Superstore Orders Analytics** is an end-to-end SQL data analysis project built using **PostgreSQL**.

The objective of this project is to transform raw order data into meaningful business insights by analyzing **sales, products, categories, customer segments, regions, states, cities, and time-based trends**.

The project demonstrates practical SQL skills from **beginner to advanced level**, including aggregation, filtering, subqueries, CTEs, date analysis, and window functions.

---

## 🎯 Business Objectives

This project answers important business questions such as:

* What is the total sales generated?
* Which category generates the highest revenue?
* Which products are the best sellers?
* Which region performs the best?
* Which customer segment generates the most sales?
* Which cities generate the highest revenue?
* What are the monthly and yearly sales trends?
* Which sub-categories contribute the most revenue?
* What percentage of total sales comes from each category?
* Which products rank highest within each category?

---

## 📂 Dataset

**Dataset:** `Source data Orders.csv`

**Total Records:** 9,994

### Dataset Features

| Column         | Description                    |
| -------------- | ------------------------------ |
| `Order Date`   | Date when the order was placed |
| `Year`         | Order year                     |
| `Month`        | Order month                    |
| `Segment`      | Customer segment               |
| `City`         | Customer city                  |
| `State`        | Customer state                 |
| `Region`       | Sales region                   |
| `Category`     | Product category               |
| `Sub-Category` | Product sub-category           |
| `Product Name` | Product name                   |
| `Sales`        | Sales amount                   |
| `Quantity`     | Quantity sold                  |

---

## 🛠️ Tools & Technologies

* PostgreSQL
* pgAdmin 4
* SQL
* CSV
* GitHub

---

## 🗄️ Database Schema

### Schema

```sql
superstore
```

### Main Table

```text
orders
```

### Table Structure

```text
orders
│
├── order_id
├── order_date
├── year
├── month
├── segment
├── city
├── state
├── region
├── category
├── sub_category
├── product_name
├── sales
└── quantity
```

---

# 🔎 SQL Analysis

## 🟢 Beginner Level

The beginner section focuses on fundamental SQL operations.

### Topics

* Total number of orders
* Total sales
* Total quantity sold
* Average sales
* Maximum sales
* Minimum sales
* Unique categories
* Unique regions
* Unique customer segments
* Sales by category
* Sales by region
* Sales by segment

### SQL Concepts

```text
SELECT
WHERE
DISTINCT
COUNT()
SUM()
AVG()
MIN()
MAX()
GROUP BY
ORDER BY
```

---

## 🟡 Intermediate Level

The intermediate section focuses on business-oriented analysis.

### Topics

* Top 10 products by sales
* Top 10 cities by sales
* Sales by state
* Sales by category and sub-category
* Monthly sales
* Yearly sales
* Average sales by category
* Above-average categories
* Category contribution to total sales
* Top-performing sub-category
* Best customer segment
* Best-performing region

### SQL Concepts

```text
CASE
HAVING
Subqueries
Aggregate Functions
Date Functions
GROUP BY
ORDER BY
```

---

# 🔴 Advanced SQL Analysis

The advanced section focuses on analytical SQL techniques.

### Topics

* Product ranking
* Product ranking within categories
* Top 3 products in each category
* Highest-selling product by category
* Running total of sales
* Monthly sales growth
* Year-over-year sales growth
* Regional sales contribution
* Above-average cities
* Above-average products
* Top sub-category within each category

### Advanced SQL Concepts

```sql
WITH
CTE
RANK()
DENSE_RANK()
ROW_NUMBER()
SUM() OVER()
AVG() OVER()
LAG()
PARTITION BY
```

---

# 📊 Key Business KPIs

| KPI               | Description                      |
| ----------------- | -------------------------------- |
| 💰 Total Sales    | Overall revenue generated        |
| 📦 Total Quantity | Total units sold                 |
| 🧾 Total Orders   | Number of orders                 |
| 📈 Average Sales  | Average sales value              |
| 🏆 Top Product    | Highest-selling product          |
| 🗂️ Top Category  | Highest-revenue category         |
| 🌎 Top Region     | Highest-performing region        |
| 🏙️ Top City      | Highest-revenue city             |
| 👥 Top Segment    | Highest-revenue customer segment |

---

# 💡 Business Insights

### 📦 Product Performance

Identify the products and sub-categories that generate the highest sales and determine which products contribute most to overall revenue.

### 🌎 Regional Performance

Compare sales across regions, states, and cities to identify strong and weak geographical markets.

### 👥 Customer Segmentation

Analyze customer segments to determine which segment contributes the highest revenue.

### 📅 Time-Based Analysis

Analyze monthly and yearly sales trends to identify changes in business performance over time.

### 🏆 Product Rankings

Use SQL window functions to identify the highest-performing products within individual categories.

### 💰 Revenue Contribution

Measure how individual categories, regions, and customer segments contribute to overall sales.

---

# 📁 Project Structure

```text
superstore-orders-analytics/
│
├── Dataset/
│   └── Source data Orders.csv
│
├── SQL/
│   ├── 01_create_schema.sql
│   ├── 02_create_table.sql
│   ├── 03_data_cleaning.sql
│   ├── 04_beginner_queries.sql
│   ├── 05_intermediate_queries.sql
│   └── 06_advanced_queries.sql
│
├── Screenshots/
│   └── query-results/
│
└── README.md
```

---

# 🚀 Future Enhancements

This project can be extended into a complete **SQL + Power BI Business Intelligence project**.

### Planned Enhancements

* 📊 Interactive Power BI dashboard
* 💰 Sales KPI cards
* 📈 Monthly sales trend
* 🗺️ Regional sales map
* 📦 Category performance dashboard
* 🏆 Product ranking dashboard
* 👥 Customer segment analysis
* 🎯 DAX measures
* 🔎 Interactive slicers
* ⭐ Star-schema data model

---

# 🎓 Skills Demonstrated

```text
SQL
PostgreSQL
Data Cleaning
Data Analysis
Business Analysis
Aggregate Functions
GROUP BY
Subqueries
CTEs
Window Functions
RANK()
DENSE_RANK()
ROW_NUMBER()
Date Analysis
KPI Analysis
Business Insights
```

---

# 📈 Project Outcome

This project demonstrates how SQL can be used to transform raw sales data into actionable business insights.

It combines **data preparation, exploratory analysis, advanced SQL techniques, and business problem-solving** to create a complete analytics workflow.

---

## ⭐ Project Objective

> **Transform raw Superstore order data into actionable business insights using PostgreSQL and advanced SQL techniques.**

---

## 👨‍💻 Author

**Bilal Idrishi**

📌 Data Analytics | SQL | PostgreSQL | Power BI

---

⭐ **If you find this project useful, consider giving the repository a star!**
