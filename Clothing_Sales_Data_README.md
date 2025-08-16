# Clothing Sales Analysis Dashboard

### Dashboard Type: Brand Performance Analytics  
### Data Source: Azure SQL Database  

---

## 📝 Problem Statement

To help e-commerce or retail stakeholders track brand-level performance based on profit %, discount %, variety count, and other KPIs. It supports identifying top and bottom brands and enables informed marketing or pricing decisions.

---

## ⚙️ Tools & Technologies Used

- **Azure SQL Database**
- **Power BI Desktop & Service**
- **DAX Functions** 
- **Power Query Editor**

---

## 🔄 Project Workflow

- Data loaded to Azure SQL and connected to Power BI using database and Microsoft account methods.
- Data cleaned and transformed inside Power Query.
- Calculated Discount %, Profit %, and Cost Price columns using DAX.
- Multiple custom visuals (from App Source) added to enhance design.

---

## 📊 Dashboard Visuals

- Multi-row Card
- Stacked Bar Chart
- Donut Chart
- Ribbon Chart
- Pie Chart
- Area Chart
- Scroller (used as a title bar for visual appeal)
---
## 📈 KPIs & DAX Metrics

Developed key performance indicators to evaluate brand profitability, pricing, and variety:  

- **Average Discount %** – Calculated per brand to assess promotional strategies  
- **Variety Count** – Number of unique products offered per brand  
- **Average Sales Price** – Identifies premium vs. budget brands  
- **Average Profit %** – Measures brand profitability trends  
- **Bottom 5 Brands by Profit %** – Flags underperforming brands for review  

DAX functions used include:  
`CALCULATE`, `DIVIDE`, `RANDBETWEEN`, `SUMX`, and `AVERAGEX` for dynamic calculations and ranking logic.  

---

## 🔄 Data Refresh Strategy

Enabled scheduled and incremental refresh in Power BI Service to optimize report performance and maintain updated data from connected sources.

---

## 🔐 Row‑Level Security

Applied RLS so each brand manager can only access data for their specific brand:

- DAX-based filters applied on brand dimension.
- Validated roles in Power BI Desktop using “View as Role”.
- Securely published via Power BI App configured for role-based access.

---
## 🚀 Deployment 

- Published to **Power BI Service**
- Shared via **Power BI App**

---

## 🔍 Business Insights & Outcomes

- Identified top 5 brands contributing the highest profit margins.  
- Highlighted brands offering excessive discounts impacting profitability.  
- Showed direct correlation between variety count and overall sales performance.  
- Helped stakeholders decide on product mix optimization and targeted promotions.  

---

## 📌 Key Learning & Real-World Relevance

Demonstrated advanced Power BI features for **brand-level analytics** integrated with Azure SQL Database.  
The approach can be applied to retail and e-commerce scenarios for monitoring **brand performance**, controlling **discount strategies**, and optimizing **inventory planning**.  

---




## 📁 Files Included

- `Clothing_Sales_Data.pbix` - Power BI report file
- `Clothing_Sales_Data_README.md` - Project documentation


---

> ⭐ *This report turns brand performance metrics into decision-ready insights by combining advanced visual storytelling and secure sharing.*
