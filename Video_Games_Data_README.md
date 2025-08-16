# Video Game Sales Analysis Dashboard

### Dashboard Type: Genre & Region-based Game Sales Analytics  
### Data Source: AWS Athena + ODBC (S3 via Glue Crawler) 

---

## 📝 Problem Statement

To help stakeholders understand the performance of video games across regions, platforms, and genres using cloud-sourced data. This dashboard provides insights into regional demand, genre preferences, and sales patterns that support marketing and product decisions.

---

## ⚙️ Tools & Technologies Used

- **Amazon Web Services (AWS S3, Athena, Glue Crawler, IAM)**
- **Power BI Desktop & Power BI Service**
- **Simba Athena ODBC Driver**
- **DAX & Power Query Editor**

---

## 🔄 Project Workflow

- Created AWS S3 bucket and uploaded game sales data.
- Used AWS Glue Crawler to scan and catalog the dataset.
- Created a database using Athena SQL Query Editor.
- Configured IAM user and permissions.
- Connected Power BI via:
  - **ODBC driver** (Simba Athena)
  - **Amazon Athena** direct connector
- Cleaned and shaped data using Power Query Editor (including **Unpivot Columns**)
- Designed a multi-page interactive dashboard

---

## 📊 Dashboard Visuals

- **Radar Chart** (sales comparison by region)
- **Bookmark Navigator** (to toggle between visual views)
- **Page Navigator** (for intuitive page switching)
- **Line Chart, Matrix, Filter Pane, Selection Pane**
- Visuals utilize **small multiples** to split genre/year views
- Report title added using a scrolling visual for better presentation

---
## 🧠 AI-Powered Insights

- Enabled Q&A visual to explore sales by genre, platform, and region using natural language.
- Used Smart Narratives to generate quick overviews of top-performing genres and regional sales.

---

## 🔄 Data Refresh Strategy

Enabled scheduled and incremental refresh in Power BI Service to optimize report performance and maintain updated data from connected sources.

---



## 🚀 Deployment

- Published to **Power BI Service**
- Delivered via workspace and apps for stakeholders

---

## 📌 Business Insights

- Identify which genres are most popular by region
- Spot trends in sales volume over time and across platforms
- Strategize regional marketing plans based on low-performing genres
- Support planning for future releases by highlighting high-demand game categories

---


## 📁 Files Included

- `Video_Games_Data.pbix` – Power BI Report file
- `Video_Games_Data_README.md` - Project documentation

---

> ⭐ *This report showcases the use of AWS cloud integration with Power BI, uncovering hidden trends in the global video game market.*
