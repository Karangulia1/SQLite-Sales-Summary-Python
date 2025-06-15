# SQLite-Sales-Summary-Python
This project demonstrates how to connect Python with a SQLite database, run SQL queries to summarize sales data, and visualize the results using matplotlib. It showcases basic database operations, data manipulation with pandas, and plotting techniques to create a simple but effective sales report. 
# 📊 Task 7: Basic Sales Summary using SQLite and Python

## 🔍 Objective
To extract and visualize basic sales data from a SQLite database using Python, SQL, pandas, and matplotlib.

---

## 🧰 Tools & Technologies
- Python 3
- SQLite (via sqlite3)
- pandas
- matplotlib
- Jupyter Notebook or Python Script

---

## 📁 Files Included
- sales_data.db - SQLite database containing sales records.
- task7_sales_summary.py - Python script for querying and visualizing sales.
- sales_chart.png - Bar chart of total revenue per product.
- Task7_Sales_Summary_Report.pdf - Final compiled report with query, output, chart, and interview Q&A.
- README.md - Overview of the project.

---

## 📊 Sample SQL Query Used
```sql
SELECT product, 
       SUM(quantity) AS total_quantity, 
       SUM(quantity * price) AS total_revenue 
FROM sales 
GROUP BY product;

## 💼 Author
*Karan*

## Linkedin Profile : (https://www.linkedin.com/in/karan-gulia-863a25281)
