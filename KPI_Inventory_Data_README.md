# Inventory Data Analysis Dashboard

### Dashboard Type: KPI Monitoring  
### Data Source: Microsoft SQL Server & MySQL
---

## 📝 Problem Statement

This dashboard helps businesses monitor key inventory performance indicators — such as product demand, availability, profit/loss, and supply shortages — across test and production environments. It ensures data consistency while switching between different database systems (SQL Server and MySQL), and provides actionable insights to reduce product shortages, control losses, and optimize stock planning.

---

## ⚙️ Tools & Technologies Used

- **Power BI Desktop & Power BI Service**
- **Microsoft SQL Server (SSMS)**
- **MySQL Workbench**
- **MySQL Connector/NET**
- **DAX (Data Analysis Expressions)**
- **SQL Joins, Views, and Query Optimization**

---

## 🔄 Project Overview

The project simulates a real-world scenario involving:

- Working with two environments: **Test** (smaller dataset) and **Production** (larger dataset)
- Connecting Power BI to different **RDBMS sources**:
  - First via **Microsoft SQL Server**
  - Then switching the data source to **MySQL**
- Performing data validation post-source switch
- Building consistent KPI-driven dashboards across both environments

---

## 🧼 Data Preparation & Cleaning

- Combined relational tables using `INNER JOIN` in both SQL Server and MySQL to unify product, pricing, and transaction data.
- Applied pre-load transformations in SSMS and MySQL Workbench to standardize column formats, handle null values, and ensure referential integrity.
- Structured schema optimized for analysis, including Product, Pricing, Sales, and Date dimensions.


---

## 🧮 DAX Measures Created

Developed a suite of KPI measures to monitor inventory efficiency and financial performance, including:
- **Average Demand & Availability Trends** – calculated using iterator functions.
- **Supply Shortage Metric** – difference between demand and availability to highlight stock gaps.
- **Profitability & Loss Tracking** – total and daily performance indicators derived from transactional data.
- **Daily Loss Analysis** – time-based loss trends to support operational decision-making.

---

## 📊 Dashboard Features

- **Slicers** for interactive filtering across KPIs
  - Fields: `Product Name`, `Order Date`
- **Card Visuals** representing each KPI for quick at-a-glance analysis
- **Advanced Editor** used to manually modify connection string when switching from SQL Server to MySQL
- **Report Pages** designed for clarity: separated into test and production views

---

## 🧠 AI-Powered Insights

- Added Q&A visual for natural language querying of profit, availability, and demand trends.
- Enabled forecasting to project potential supply shortages and losses using historical data.

---
## 🔄 Data Refresh Strategy

Enabled scheduled and incremental refresh in Power BI Service to optimize report performance and maintain updated data from connected sources.

---
## 🔐 Row‑Level Security

Implemented RLS in Power BI to restrict access by user role:
- Product or region managers only view their assigned segments.
- Defined roles using DAX filters and validated via “View as Role” in Power BI Desktop.
- Deployed securely in Power BI Service to enforce access control.

---
## 🚀 Deployment & Validation

- Report published to **Power BI Service**
- Source successfully switched from **Microsoft SQL Server** to **MySQL** using advanced editor
- Full **data validation** was conducted post-switch to ensure consistency in KPIs

---
## 🔍 Business Insights & Outcomes

- Identifies **top-performing products** based on profit contribution
- Reveals **high-demand items** with insufficient availability
- Flags areas with **daily recurring losses** to prioritize action
- Assists in **stock planning** by analyzing average demand vs. availability
- Highlights the value of flexible architecture through **multi-source integration**

---





## 📌 Key Learning & Real-World Relevance

This project strengthened skills in:
- **Cross-platform data integration**
- **Database source migration in Power BI**
- **Advanced DAX KPI calculation**
- **Report storytelling from operational datasets**
- **Data validation in multi-environment deployments**

---

## 📁 Files Included

- `KPI_Inventory_Data.pbix` – Power BI report
- `KPI_Inventory_Data_README.md` – Project documentation

---

> ⭐ *This project demonstrates how cross-environment analytics and KPI visibility can directly support business operations and reduce inefficiencies in product inventory management.*
