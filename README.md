# Retail-SQL-project

# 🛍️ Retail Sales Analysis | SQL Project

## 📌 Project Overview

This project focuses on analyzing retail sales data using SQL. The main objective is to explore sales transactions, customer demographics, product categories, and purchasing patterns to answer important business questions.

The project demonstrates SQL-based data cleaning, data manipulation, aggregation, and business analysis.

## 🎯 Objectives

- Clean and preprocess retail sales data.
- Identify and handle missing values.
- Standardize customer gender information.
- Analyze total sales and transactions by product category.
- Understand customer purchasing behavior.
- Identify high-value sales transactions.
- Analyze monthly sales performance.
- Explore customer preferences based on gender and product category.
- Analyze sales patterns based on different time shifts.

## 🛠️ Technologies Used

- SQL
- Relational Database
- SQL Query Editor

## 📂 Dataset Information

The project uses a retail sales dataset containing the following attributes:

| Column Name | Description |
|---|---|
| transaction_id | Unique transaction ID |
| sale_date | Date of transaction |
| sale_time | Time of transaction |
| customer_id | Customer identification number |
| gender | Gender of customer |
| age | Age of customer |
| category | Product category |
| quantity | Quantity purchased |
| price_per_unit | Price of each unit |
| cogs | Cost of goods sold |
| total_sale | Total sales amount |

## 🧹 Data Cleaning

The following data cleaning operations are performed:

1. Checked the dataset for NULL values.
2. Identified incomplete records.
3. Removed records containing NULL values.
4. Standardized gender values:
   - M → Male
   - F → Female
5. Verified the cleaned data.

### SQL Concepts Used

- SELECT
- WHERE
- DELETE
- UPDATE
- DISTINCT

## 📊 Business Questions and SQL Analysis

The project answers the following 10 business questions:

**Q1.** Retrieve all columns for sales made on November 5, 2022.

**Q2.** Retrieve all transactions where the category is Clothing, quantity sold is greater than 2, and the transaction occurred in November 2022.

**Q3.** Calculate total sales revenue and the total number of transactions for each product category.

**Q4.** Find the average age of customers who purchased products from the Beauty category.

**Q5.** Retrieve all transactions where total sales exceeded or equaled 1000.

**Q6.** Calculate the total number of transactions made by each gender in each product category.

**Q7.** Calculate total monthly sales for each year and identify the best-selling month in each year.

**Q8.** Retrieve the five transaction records with the highest total sales.

**Q9.** Calculate the number of unique customers who purchased products from each category.

**Q10.** Categorize transactions into Morning, Afternoon, and Evening shifts and count the orders in each shift.

## 🧠 SQL Skills Demonstrated

This project covers the following SQL concepts:

- Data Cleaning and Data Manipulation
- Aggregate Functions: SUM(), AVG(), COUNT()
- GROUP BY and ORDER BY
- WHERE and DISTINCT
- UPDATE and DELETE
- CASE Statements
- Common Table Expressions (CTE)
- Window Functions
- RANK()
- Date and Time Functions
- Subqueries and Filtering

## 📁 Project Structure

```text
Retail-Sales-SQL-Analysis/
│
├── SQL.sql
└── README.md
```

## ⚙️ How to Run the Project

**Step 1:** Clone the repository.

```bash
git clone https://github.com/Anjalisatdeve/Retail-SQL-project
```

**Step 2:** Open the SQL file in your SQL database environment.

**Step 3:** Create the database and retail_sales table using the complete dataset schema.

**Step 4:** Import the retail sales dataset.

**Step 5:** Execute the SQL queries one by one.

**Step 6:** Review the query outputs to understand the sales patterns and business insights.

## 💡 Key Learning Outcomes

- Understanding real-world SQL data cleaning operations.
- Writing queries to solve business-related problems.
- Analyzing sales using aggregate functions.
- Working with date and time-based data.
- Using CTEs and window functions for advanced analysis.
- Extracting meaningful information from retail transaction data.

## 🏁 Conclusion

This project demonstrates how SQL can be used to analyze retail sales data and solve practical business problems.

Through data cleaning and SQL queries, the project explores sales performance, customer demographics, product categories, transaction values, and purchasing time patterns.

It provides practical experience in SQL and strengthens the ability to perform data analysis using relational databases.

---

## 👨‍💻 Author

**Anjali Satdeve**

GitHub: https://github.com/Anjalisatdeve

---

⭐ If you find this project useful, don't forget to star the repository!
