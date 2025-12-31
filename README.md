# 🚴 BikeStore Sales Performance Analysis  
**End-to-End Business Analytics Case Study using SQL & Power BI**

---

## 📌 Project Overview
This project is a complete **retail business analytics case study** built using **SQL and Power BI**.  
The objective is to analyze sales performance, identify revenue drivers, evaluate discount impact, and generate actionable insights across **products, categories, stores, staff, and time** to support data-driven business decisions.

The project follows a **real-world analytics workflow** — from raw data exploration and SQL validation to interactive dashboarding and executive-level insights.

---

## 🎯 Business Objectives
- Analyze overall **sales and revenue performance**
- Identify **top-performing products, categories, and stores**
- Understand the **impact of discounts on net revenue**
- Analyze **seasonal, weekly, and daily sales trends**
- Evaluate **store and staff performance**
- Provide **actionable business recommendations**

---

## 🗂 Dataset Overview
The analysis is based on a real-world **BikeStore retail dataset** consisting of **9 relational tables**.

### 📊 Tables Used
- `orders` – Order-level details (order date, customer, store)
- `order_items` – Transaction-level sales data (quantity, price, discount)
- `customers` – Customer master data
- `products` – Product information
- `categories` – Product categories
- `brands` – Bike brands
- `stores` – Store details
- `staffs` – Sales staff information
- `stocks` – Inventory data

### 🧠 Data Model
- **Fact Table:** `order_items`
- **Dimension Tables:** customers, products, categories, brands, stores, staffs, orders
- **Grain:** Order-item level (each row represents a product sold in an order)

---

## 🧮 SQL Analysis
All KPIs and insights were **validated using SQL before visualization**.

### 🔑 SQL Concepts Used
- Multi-table joins
- Aggregations (`SUM`, `COUNT`, `AVG`)
- Common Table Expressions (CTEs)
- Window functions (`RANK`, `RUNNING TOTAL`)
- Date-based analysis (daily, weekly, monthly trends)

### 📈 Key Metrics Calculated
- Total Revenue
- Net Revenue (after discounts)
- Total Orders
- Total Customers
- Average Order Value (AOV)
- Category-wise Revenue
- Store-wise Revenue
- Staff Performance Ranking
- Seasonal, Weekly, and Daily Trends

> 📌 All Power BI KPIs are backed by SQL query outputs to ensure accuracy.

---

## 📊 Power BI Dashboard
An interactive **Power BI dashboard** was built to convert SQL-validated metrics into business-friendly visuals.

### 🔍 Dashboard Highlights
- KPI Cards: Revenue, Orders, Customers, AOV, Discount %
- Monthly & Weekly Revenue Trends
- Category-wise and Product-wise Performance
- Store-wise and Staff-wise Comparison
- Discount vs Revenue Impact Analysis

⬇ **Download Power BI Dashboard (.pbix):**  
https://raw.githubusercontent.com/yashjani1997/BikeStore-BusinessCase-Study/main/BikeStoreDashBoard.zip  
*(Unzip the file and open it in Power BI Desktop)*

---

## 💡 Key Business Insights
- **Mountain Bikes** generate the highest revenue but also carry margin risk due to high discounting.
- Revenue is concentrated among a limited set of products, indicating **portfolio dependency risk**.
- **Baldwin Bikes** outperforms other stores in both revenue and order volume.
- Sales show strong **seasonality** with identifiable peak months.
- **Weekends and Mondays** consistently outperform mid-week sales.
- Top-performing staff members significantly influence overall store performance.

---

## 📌 Business Recommendations
- Implement **category-specific discount strategies** to protect profit margins.
- Reduce dependency on a small number of high-revenue products.
- Replicate best practices from top-performing stores and staff.
- Launch targeted campaigns during high-performing seasons and weekdays.

---

## ⚠️ What I Didn’t Do & Why
- **Sales Forecasting:** Future data was not available.
- **Customer Lifetime Value (CLV):** Repeat purchase lifecycle data was missing.
- **Inventory Optimization:** Stock movement analysis was outside project scope.

---

## 🛠 Tools & Technologies
- **SQL** – Data extraction, transformation, and validation
- **Power BI** – Data visualization and dashboarding
- **GitHub** – Version control and project sharing

---

## 🏆 Project Outcome
This project demonstrates the ability to:
- Translate raw data into **accurate, SQL-validated business metrics**
- Build **insight-driven Power BI dashboards**
- Think beyond visuals and deliver **business-focused recommendations**
- Present analytics work in a **professional, recruiter-ready format**

---

## 👤 Author
**Yash**  
Data Analyst | SQL • Power BI • Business Analytics
