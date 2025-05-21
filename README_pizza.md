
# 🍕 Crusto Pizza – SQL-Based Sales Analysis

> *"Helping Crusto Pizza grow smarter, slice by slice!"*

This project is a data-driven sales analysis of a fictional pizza brand, **Crusto Pizza**, using SQL to uncover critical insights that inform business strategies. From identifying best-selling pizzas to analyzing order patterns by time and category, the project demonstrates how data can be turned into actionable decisions in the food industry.

---

## 📌 Project Objective

The goal is to analyze Crusto Pizza's order and sales data to answer key business questions, such as:
- Which pizza sizes and types are most popular?
- What products contribute the most to revenue?
- When are customers most likely to place orders?
- How is revenue distributed over time and across categories?

---

## 🧠 Key Business Insights

| 🔍 Analysis | 💡 Insight |
|------------|------------|
| **Total Orders** | Total number of orders placed by customers |
| **Revenue Generated** | Total revenue from all pizza sales |
| **Top-Selling Pizzas** | The 5 most ordered pizza types by quantity |
| **Most Popular Size** | Most frequently ordered pizza size |
| **Top Revenue Contributors** | Pizza types that generate the most revenue |
| **Hourly Order Trends** | Peak hours when most orders are placed |
| **Daily Pizza Orders** | Average number of pizzas ordered per day |
| **Category Breakdown** | Pizza categories with highest order volume and revenue |
| **Cumulative Revenue** | Revenue growth over time (time series pattern) |

---

## 🧮 Techniques Used

- ✅ SQL (GROUP BY, JOIN, ORDER BY, AGGREGATE functions)
- ✅ Subqueries and nested queries
- ✅ Time-based and category-wise analysis
- ✅ Revenue contribution and cumulative tracking

---

## 🗃️ Sample Queries Performed

- `SELECT COUNT(*) FROM orders` – total order count  
- `SUM(price * quantity)` – total revenue calculation  
- `GROUP BY pizza_type ORDER BY SUM(quantity)` – top pizzas  
- `GROUP BY size` – most common size  
- `GROUP BY HOUR(order_time)` – order distribution by time of day  
- `GROUP BY category` – performance by category

---

## 📈 Potential Use Cases

- 📊 **Business Intelligence Dashboards** (Power BI, Tableau)
- 📦 **Inventory Planning** based on peak demand periods
- 💸 **Promotional Strategy** for high-revenue pizzas
- 📅 **Operational Planning** based on time-wise order trends

---

## 🛠️ Tools & Technologies

- **SQL** – Core language for data extraction and analysis  
- **Excel / Google Sheets** – Optional for EDA presentation  
- **Power BI/Tableau** *(future scope)* – For building dashboards  

---

## 📁 Folder Structure

```
├── pizza_sales_project.sql
├── pizza_sales_dataset.csv
├── pizza_sales_report.pdf
└── README.md  👈
```

---

## 🙌 Thank You

This project showcases how **SQL-powered analysis** can help food service businesses optimize operations and sales strategies.  
Feel free to explore the queries, insights, and replicate it for your own datasets!
