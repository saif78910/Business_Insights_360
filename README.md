# 💼 Business Insights 360 | Power BI Project

This project is part of the **Power BI Course** by [Codebasics](https://www.codebasics.io/) and simulates a real-world business scenario where **AtliQ Hardware** seeks to build its first data analytics capability. The goal is to drive data-informed decisions across departments such as Finance, Sales, Marketing, and Supply Chain.

🔗 **Live Report**: _[Add Your Power BI Report Link Here]_  
🎓 **Course Link**: [SQL + Power BI for Data Analytics](https://www.codebasics.io/)

---

## 🧰 Tech Stack

- SQL  
- Power BI Desktop  
- Excel  
- DAX Language  
- DAX Studio  
- Git + GitHub LFS

---

## 🧠 Power BI Skills Gained

- Project Kickoff: Key questions to ask stakeholders  
- Creating calculated columns & measures using DAX  
- Data modeling using Snowflake schema  
- Creating Date tables using M language  
- Dynamic titles and KPI indicators  
- Conditional formatting using icons and colors  
- Bookmarks & Page navigation  
- Power BI Services (publishing, auto-refresh via gateway, collaboration & access management)  
- Power BI App creation  
- Data validation techniques

---

## 🗂 Dataset Overview

### 🧾 Source: MySQL Database (Imported to Power BI)

#### Dimension Tables:
- `dim_customer`: Markets, customer platforms (e.g., E-commerce, Brick & Mortar), and sales channels  
- `dim_market`: 27 markets across 4 regions (APAC, EU, LATAM, etc.)  
- `dim_product`: Divisions like P&A, N&S, and categories like HDDs, notebooks, etc.

#### Fact Tables:
- `fact_sales_monthly`: Monthly actual sales quantity  
- `fact_forecast_monthly`: Forecasted quantity per customer  
- `freight_cost`: Market-wise transportation and other costs  
- `gross_price`, `manufacturing_cost`: Pricing and cost information  
- `pre_invoice_deductions`, `post_invoice_deductions`: Discounts and deductions

---

## 🧱 Data Modeling Approach

- **Model Type**: Snowflake Schema  
- **Best Practices Followed**: Star schema principles, relationship optimization, data normalization where needed  
- **Note**: Poor modeling can degrade report performance. Optimization done using **DAX Studio**

---

## 📊 Dashboard Views

- **Home View**: Navigation to different sections  
- **Info Page**  
- **Finance View**  
- **Sales View**  
- **Marketing View**  
- **Supply Chain View**  
- **Executive Summary**  
- **Products View**  
- **Support Page**

Each view is built using intuitive visuals, KPI cards, filters, and dynamic elements to ensure a seamless user experience.

---

## ❓ Business Questions Explored

Before building the dashboard, we addressed key questions:
- What is the goal of the dashboard?
- How will success be measured?
- What are the stakeholder expectations and fears?
- What data is needed and who are the users?
- What could go wrong during development?

---

## 🏢 Company Background

**AtliQ Hardware** is a fast-growing company specializing in computers and accessories. It operates across the globe via:
- **Retailers**
- **Distributors**
- **Direct Sales**

After facing losses due to poor forecasting and lack of data insights, AtliQ is building an analytics team and Power BI dashboards to support data-driven decision-making.

---

## 🧮 Business Terms Covered

- Gross Price  
- Pre & Post Invoice Deductions  
- Net Invoice Sale  
- Gross Margin, Net Sales, Net Profit  
- COGS (Cost of Goods Sold)  
- YTD (Year to Date), YTG (Year to Go)
- Direct, Retailer, Distributors, Consumer
---

## 🚀 Final Thoughts

This project was a comprehensive end-to-end data analytics solution using Power BI, built on top of real-world business scenarios and driven by solid SQL and DAX foundations. It not only improved my technical capabilities but also enhanced my understanding of business operations, stakeholder communication, and dashboard storytelling.

---

