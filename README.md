# task2-with-code-tech
# 📊 Data Analysis with Complex SQL Queries
This project demonstrates advanced data analysis using **MySQL**.
- It uses complex SQL features such as **subqueries**, **common table expressions (CTEs)**, and **window functions** to derive meaningful insights from a sales dataset.

## 📁 Project Structure

- `create_tables.sql` - SQL script to create and populate the Sales table.
- `queries.sql` - Contains all the complex SQL queries used for analysis.
- `report.pdf` - Final report with insights and screenshots of query results. *(Optional, include if you upload this)*
- `README.md` - Project documentation.

## 🧠 Concepts Used

- ✅ Subqueries  
- ✅ Common Table Expressions (CTEs)  
- ✅ Window Functions (`RANK()`, `SUM() OVER`, etc.)  
- ✅ Aggregate Functions (`SUM`, `AVG`)  
- ✅ Grouping and Filtering

## 🗂 Sample Dataset

A fictional `Sales` dataset is used, containing:

| SaleID | CustomerID | Product     | Amount   | SaleDate   |
|--------|------------|-------------|----------|------------|
| 1      | 101        | Laptop      | 85000    | 2024-01-15 |
| 2      | 102        | Phone       | 40000    | 2024-01-17 |
| ...    | ...        | ...         | ...      | ...        |

## 📌 Key Analyses

1. **Above-Average Sales**  
   Identify all sales with amounts above the average using a subquery.

2. **Monthly Sales Totals**  
   Use a CTE and `DATE_FORMAT()` to summarize sales by month.

3. **Cumulative Monthly Sales**  
   Use a window function (`SUM() OVER`) to calculate cumulative totals over time.

4. **Customer Purchase Ranking**  
   Rank purchases per customer based on transaction amount.

## 📝 Report Summary

Insights include:
- Peak sales periods and trends
- High-spending customers
- Product performance across time

## ✅ Requirements

- MySQL 8.0+
- Any SQL client (e.g., MySQL Workbench, DBeaver, phpMyAdmin)

## 🎓 Internship Completion

This project was completed as part of the **CodTech Internship Program** on **Advanced SQL Data Analysis**. A certificate of completion will be issued upon final review.

## 📬 Contact

For any queries or feedback, feel free to reach out.

- 👤 Name: *NAVEEN GUNA*
- 📧 Email: *naveenguna1009@gmail.com*
- 🔗 GitHub: [github.com/NaveenG05](https://github.com/NaveenG05)

