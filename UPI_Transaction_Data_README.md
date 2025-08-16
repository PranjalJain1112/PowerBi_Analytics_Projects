# UPI Transaction Data Analysis Dashboard

### Dashboard Type: Digital Payments Analytics  
### Data Source: Snowflake Data Warehouse  
---

## 📝 Problem Statement

This dashboard provides a comprehensive analysis of UPI transaction patterns across demographics, payment modes and time periods. It is designed to help payment service providers, banks and financial analysts understand consumer behavior, detect anomalies and optimize payment systems.

---

## ⚙️ Tools & Technologies Used

- **Power BI Desktop & Power BI Service**
- **Snowflake** (as data warehouse)
- **DAX (Data Analysis Expressions)**
- **Snowflake SQL for data preparation**

---

## 🔄 Project Overview

The project focuses on building an interactive analytics solution for UPI transaction data:
- Connected Power BI directly to **Snowflake**.
- Cleaned and optimized data inside Snowflake before importing.
- Applied Power Query transformations for additional formatting.
- Created interactive report pages for detailed insights into transaction patterns.
  
---

## 🧼 Data Preparation & Cleaning

- Data cleaning performed in **Snowflake SQL** to remove nulls, format dates, and optimize joins.
- Additional transformations handled within Power Query in Power BI.
- Created calculated columns in DAX for Age Group classification and payment method categorization.

---

## 🧮 DAX Measures Created

Developed key analytical measures to evaluate transaction performance and consumer patterns:

- **Volume & Value Metrics** – Total transaction count, total transaction value, and average value per transaction for high-level financial analysis.
- **Demographic Segmentation** – Age group classification and gender-based transaction breakdown using conditional logic in DAX.
- **Payment Method Analysis** – Dynamic categorization of UPI-based payment types to assess adoption trends.
- **Trend Indicators** – Time-based measures to track transaction patterns across different periods.
---

## 📊 Dashboard Features

- **Slicers** for dynamic filtering by age, gender, payment mode, transaction date, and region.
- **Line Charts** for time-series transaction trend analysis.
- **Stacked Bar Charts** for gender, age group, and payment method distribution.
- **Matrix Table** for transaction details with conditional formatting.
- **Bookmark Navigator & Page Navigation Buttons** for enhanced UX.
- Use of Selection, Bookmark and Sync Slicers and Filter Pane.
- **Drill-down** functionality for deeper data exploration.

---
## 🧠 AI-Powered Insights

- Used **Decomposition Tree** to explore transaction patterns across age, gender, and payment method.
- Applied **Anomaly Detection** to identify irregular spikes in daily transactions.

---
## 🔄 Data Refresh Strategy

Enabled scheduled and incremental refresh in Power BI Service to optimize report performance and maintain updated data from connected sources.

---

## 🔍 Business Insights & Outcomes

- Identified peak transaction periods by day and month.
- Segmented spending patterns by gender and age group.
- Highlighted top payment modes contributing to transaction volume.
- Detected irregular spikes in UPI transactions indicating potential anomalies.

---

## 📌 Key Learning & Real-World Relevance

This project demonstrates:
- Connecting Power BI with **Snowflake Cloud Data Warehouse**
- Designing **consumer transaction analytics** for the fintech industry
- Implementing **user-friendly navigation** and **storytelling dashboards**

---

## 📁 Files Included

- `UPI_Transaction_Data` – Power BI report file  
- `UPI_Transaction_Data_README.md` – Project documentation 

---

> ⭐ *This project showcases advanced UPI transaction analytics using cloud data warehousing and Power BI's interactive visual storytelling capabilities.*
