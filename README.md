# 🍕 Pizza Sales Analysis | SQL Business Intelligence Project

![SQL](https://img.shields.io/badge/SQL-MySQL-blue)
![Analytics](https://img.shields.io/badge/Focus-Business%20Analytics-green)
![Level](https://img.shields.io/badge/Level-Intermediate%20to%20Advanced-orange)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

---

## 📌 Project Overview

This project performs an end-to-end sales analysis of a pizza restaurant dataset using **MySQL**.  
The goal was to answer structured business questions (Basic → Intermediate → Advanced) using SQL and generate actionable insights from transactional sales data.

All questions provided in `Questions.txt` were solved, and the SQL queries with outputs are documented in the final report:

📄 **Pizza sales analysis project.pdf**

This project demonstrates practical SQL skills used in real-world data analyst and business intelligence roles.

---

## 🎯 Business Objectives

The analysis answers key business questions such as:

- What is the total number of orders?
- How much total revenue was generated?
- Which pizzas drive the highest revenue?
- What are the most popular pizza sizes?
- How do sales vary by hour of the day?
- What is the cumulative revenue trend over time?
- Which pizzas perform best within each category?

---

## 🗂 Dataset Description

The project uses four relational tables:

| Table Name        | Description |
|------------------|-------------|
| `orders`         | Order ID, order date, order time |
| `order_details`  | Quantity and pizza reference per order |
| `pizzas`         | Pizza size and price |
| `pizza_types`    | Pizza name and category |

The tables are connected using primary and foreign keys to perform multi-table joins and relational analysis.

---

## 🧠 SQL Skills Demonstrated

### 🔹 Fundamental SQL
- `COUNT()`
- `SUM()`
- `ROUND()`
- `GROUP BY`
- `ORDER BY`
- `LIMIT`

### 🔹 Intermediate SQL
- Multi-table `JOIN`
- Category-level aggregation
- Hourly order distribution
- Daily average sales calculation

### 🔹 Advanced SQL
- Revenue percentage contribution
- Window functions (`OVER`, `ROW_NUMBER`)
- Cumulative revenue analysis
- Ranking top products within each category

---

## 📊 Key Insights

| KPI | Result |
|-----|--------|
| Total Orders | **21,350** |
| Total Revenue | **$817,860.05** |
| Highest Priced Pizza | **The Greek Pizza** |
| Most Ordered Size | **Large** |
| Top Revenue Pizza | **The Thai Chicken Pizza** |
| Avg Pizzas Sold Per Day | **138** |

### Additional Findings

- The **Classic category** contributes the highest revenue share.
- Peak ordering hours occur between **12 PM – 1 PM** and **5 PM – 7 PM**.
- Revenue shows steady cumulative growth over time.
- Chicken-based pizzas dominate top revenue rankings.

(Full query outputs available in the PDF report.)

---

## 📁 Project Structure
├── Questions.txt
├── Pizza sales analysis project.pdf
├── orders.csv
├── order_details.csv
├── pizzas.csv
└── pizza_types.csv


---

## 🛠 Tools & Technologies

- **MySQL**
- SQL (Advanced Querying)
- Relational Database Modeling
- Data Aggregation & KPI Analysis
- Business-Oriented Reporting

---

## 🚀 How to Run This Project

1. Import the CSV files into MySQL.
2. Create tables based on the dataset structure.
3. Execute the SQL queries.
4. Compare your outputs with the provided PDF report.

---

## 📈 Business Value of This Analysis

This project simulates real-world business analytics scenarios such as:

- Product performance evaluation
- Revenue contribution analysis
- Peak hour identification
- Category-level strategic insights
- Sales trend monitoring

These skills are directly applicable to roles in:

- Data Analytics  
- Business Intelligence  
- Commercial Analytics  
- Retail / Food Industry Analytics  
- Automotive & Manufacturing Sales Analytics  

---

## 💼 Why This Project Matters

This project highlights:

✔ Strong SQL querying capability  
✔ Ability to work with relational databases  
✔ Revenue and KPI-driven analysis  
✔ Window function proficiency  
✔ Translating raw data into business insights  

---

## 👨‍💻 Author

**Muhammad Ahmed Memon**  
MSc Computer Science  
Aspiring Data Analyst | SQL | Machine Learning  

---

⭐ If you found this project useful, feel free to star the repository.
