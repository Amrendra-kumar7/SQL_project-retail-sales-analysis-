# 🛒 Retail Sales Analysis using SQL

This project focuses on analyzing retail sales data using **PostgreSQL**. It involves importing a transactional dataset, creating a structured database, and running meaningful SQL queries to extract business insights.

---

## 📌 Project Highlights

- Written in: **PostgreSQL**
- Managed using: **pgAdmin 4**
- File Imported: `retail_sales.csv`
- SQL File: `SQL_project(Retail_sales_analysis).sql`

---

## 📂 Dataset Description

The dataset contains detailed retail transactions including sales, customer demographics, and product information.

| Column Name      | Description                          |
|------------------|--------------------------------------|
| `transactions_id`| Unique ID for each transaction       |
| `sale_date`      | Date of sale                         |
| `sale_time`      | Time of sale                         |
| `customer_id`    | Unique customer ID                   |
| `gender`         | Gender of customer                   |
| `age`            | Age of customer                      |
| `category`       | Product category                     |
| `quantity`       | Units sold                           |
| `price_per_unit` | Price per unit of product            |
| `cogs`           | Cost of goods sold                   |
| `total_sale`     | Total sale amount                    |

---

## 📊 What I Did

- Created a PostgreSQL table to store retail transactions
- Imported data from CSV using pgAdmin
- Ran multiple SQL queries to:
  - Calculate daily, monthly, and total sales
  - Analyze sales by gender, category, and age
  - Identify top-selling products
  - Compare total sales and COGS (profitability)
  - Segment customers based on demographics and purchase behavior

---

## 🧠 Sample Business Questions Answered

- Which product categories generate the most revenue?
- What are the peak sales times during the day?
- How does customer gender or age influence purchase decisions?
- Who are the top customers by total purchase value?

---

## 🛠️ Tools Used

- **PostgreSQL**
- **pgAdmin 4**
- **SQL (DDL, DML, Aggregates, Filtering, Grouping)**

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/retail-sales-sql-analysis.git
