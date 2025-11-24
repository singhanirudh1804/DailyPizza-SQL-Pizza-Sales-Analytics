# 🍕 DailyPizza – SQL Pizza Sales Analytics

A complete SQL-based data analysis project using four interconnected datasets to extract meaningful business insights such as revenue trends, top-selling pizzas, demand patterns, and category-wise performance.

---

## 📌 Project Overview

**DailyPizza** is an end-to-end SQL analytics project built using a real-world pizza sales dataset containing orders, order details, pizza information, and pizza categories.
The objective is to explore sales performance, identify top contributors, and answer business-critical questions through SQL queries of varying complexity.

---

## 📂 Dataset Description

The project uses **4 CSV datasets**:

| File                | Description                                            |
| ------------------- | ------------------------------------------------------ |
| `orders.csv`        | Contains order timestamps and order IDs                |
| `order_details.csv` | Items ordered in each order (pizza_id, quantity, etc.) |
| `pizzas.csv`        | Pizza sizes, prices, and pizza type reference          |
| `pizza_types.csv`   | Pizza names, ingredients, and categories               |

---

## 🧠 Skills Demonstrated

* SQL Joins (INNER JOIN, LEFT JOIN)
* Aggregate Functions (SUM, COUNT, AVG, MAX)
* Window Functions (ROW_NUMBER, RANK, CUME_DIST)
* Date & Time Functions
* Grouping and Subqueries
* Analytical Problem-solving with SQL

---

## 🔍 Problem Statements & Solutions

### ✅ **Basic Queries**

* Total number of orders placed
* Total revenue generated
* Highest-priced pizza
* Most common pizza size ordered
* Top 5 most ordered pizza types

---

### 🔄 **Intermediate Queries**

* Category-wise total quantity ordered
* Distribution of orders by hour
* Category-wise distribution of pizzas
* Average number of pizzas ordered per day
* Top 3 pizzas by revenue

---

### 🚀 **Advanced Queries**

* Percentage contribution of each pizza type to total revenue
* Cumulative revenue over time
* Top 3 pizzas by revenue within each category

---

## 🗂 Folder Structure

```
DailyPizza/
│── data/
│   ├── orders.csv
│   ├── order_details.csv
│   ├── pizzas.csv
│   ├── pizza_types.csv
│
│── queries/
│   ├── basic_queries.sql
│   ├── intermediate_queries.sql
│   ├── advanced_queries.sql
│
│── README.md
```

---

## 🛠 How to Run the Project

1. Import the CSV files into your SQL environment (MySQL / PostgreSQL / SQLite).
2. Create tables according to the dataset structure.
3. Load the dataset using `LOAD DATA INFILE` or import tools.
4. Run queries from the `queries/` folder to reproduce the analysis.

---

## 📈 Key Insights from Analysis

* The most popular pizza size is **Medium (M)**.
* The top-selling pizza types contribute a major portion of the revenue.
* Revenue shows meaningful cumulative growth over time.
* Certain categories dominate demand (e.g., Classic, Supreme).

---

## 🎯 Project Highlights

* 🔹 Solved 15+ business-focused SQL queries
* 🔹 Applied both simple and advanced SQL concepts
* 🔹 Demonstrates real-world analytical thinking
* 🔹 Perfect for Data Analytics & Data Science profiles

---

## 🤝 Contributing

Feel free to fork this repository and submit improvements.

---

## 📧 Contact

**Anirudh Singh**
Data Analyst | SQL | Python | ML

✅ A **project thumbnail image**
Just tell me!
