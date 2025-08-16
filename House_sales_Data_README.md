# Housing Data Analysis Dashboard

### Dashboard Type: Real Estate Sales & Trend Analytics  
### Data Source: Google BigQuery  


---

## 📝 Problem Statement

This dashboard enables stakeholders to monitor housing market KPIs, regional sales and trends over time to support development and pricing strategy.

---

## ⚙️ Tools & Technologies Used

- **Google BigQuery**
- **Power BI Desktop & Service**
- **Power Query** 
- **DAX (Data Analysis Expressions)**
---

## 🔄 Project Workflow

- Connected and integrated housing sales data from Google BigQuery into Power BI for large-scale trend analysis.  
- Applied Power Query transformations for data formatting, cleansing, and enrichment.  
- Developed advanced DAX measures for YOY growth, rolling trends, and median pricing insights.  
- Designed an interactive, multi-page dashboard combining KPIs with drill-through capabilities for deeper analysis.  
- Incorporated AI visuals (Smart Narratives, Q&A) and Key Influencers for better data storytelling.
---


## 🧱 Data Modeling Approach

- Followed a **Star Schema** structure with a central fact table and dimension tables for region, time, and sales type.
- Configured **active relationships** to manage default filter paths across model tables.
- Set appropriate **cross filter direction** (single/both) to support correct DAX logic and interactivity.

---

## 🧮 Key DAX Measures

Designed analytical measures to provide both **historical trends** and **forward-looking perspectives**:

- **Growth & Trend Analysis** – Leveraged `CALCULATE`, `TOTALYTD`, and `DATESINPERIOD` to compute year-over-year growth and rolling period trends.
- **Market Pricing Intelligence** – Used `MEDIANX` to monitor price movements and detect shifts in median sales across different regions and timeframes.
- **Context-Aware Metrics** – Applied `ALLEXCEPT` and logical functions (`IF`, `BLANK`) to ensure accurate KPI calculations while respecting user-selected filters.
- **Time-Based Segmentation** – Implemented `YEAR` and `QUARTER` for seasonal sales performance analysis.

---

## 📊 Dashboard Features

- **Market Trends & KPIs** – At-a-glance metrics for YOY growth, median price, and units sold.  
- **Regional & Sales Type Insights** – Interactive comparisons by geography and sales category.  
- **Key Driver Analysis** – Key Influencers visual to surface factors impacting sales outcomes.  
---
## 🧠 AI-Powered Insights

- Integrated Q&A visual to enable natural language.
- Used Smart Narratives to automatically summarize regional and yearly housing trends.

---
## 🔄 Data Refresh Strategy

- Enabled scheduled refresh in Power BI Service to maintain up-to-date reports.
- For larger datasets, incremental refresh was configured for optimized performance.

---
## 🚀 Deployment & Publishing

- Report published to **Power BI Service**
- Shared with team via workspace

---
## 🔍 Business Insights & Outcomes

- Identified **year-over-year growth trends** in housing sales, highlighting periods of peak market activity.
- Revealed **regional performance patterns**, enabling targeted development strategies in high-demand areas.
- Assessed **median sales price changes** by region to guide pricing strategies.
- Analyzed **unit sales distribution by sales type** to optimize portfolio mix.
- Measured **average square meter per sale** by region, aiding in property sizing decisions.
---



## 📌 Key Learning & Real-World Relevance

Demonstrated how to integrate cloud-hosted datasets from Google BigQuery into Power BI, apply star schema modeling for performance, and deliver market intelligence for real estate.  
Insights such as price trends, sales drivers, and regional performance can directly guide development planning and pricing strategies.

---



## 📁 Files

- `House_sales_Data.pbix`
- `House_sales_Data_README.md`

---

> ⭐ *This report merges location intelligence and housing trends into a structured, cloud-connected dashboard experience.*
