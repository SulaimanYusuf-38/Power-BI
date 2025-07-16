# 🚴 AdventureWorks Power BI Dashboard

This project is an interactive Power BI report built on the AdventureWorks dataset. It focuses on analyzing customer behavior, product returns, revenue performance, and sales trends over time.

## 📊 Project Overview

The dashboard is designed to help business stakeholders and analysts:

- Track revenue, orders, returns, and profit metrics
- Understand customer demographics and top customer value
- Monitor return rate and product performance
- Explore key drivers of product pricing and customer attributes

---

## 📁 File Contents

| File | Description |
|------|-------------|
| `AdventureWorkSpace.pbix` | Power BI Desktop file with full dashboard and model |
| `screenshots/` | Folder containing key visuals from the report |
| `Model View.png` | Data model with relationships (star schema) |
| `Summary Dashboard.png` | Main KPI dashboard |
| `Product Detail.png` | Daily trends, anomalies, and return rate by product |
| `Customer Detail.png` | Revenue breakdown by customer, income, and occupation |
| `Decomposition Tree.png` | Return rate analysis by continent, category, and product |
| `Key Influencers.png` | Key Drivers affecting Home Ownership and Retail Price |

---

## 🔍 Key Insights

### 📈 Sales Performance Dashboard
- **$24.9M in revenue**, **10.5M in profit**, with over **25.2K orders**
- Return rate consistently hovers around **2.2%**
- Revenue and returns spike seasonally, with clear upward trends

### 👥 Customer Analysis
- **17.4K unique customers** with average revenue of **$1,431 per customer**
- High-revenue segments are concentrated in management and professional occupations
- Top 100 customers contribute a significant portion of revenue

### 🚚 Product Return Analysis
- Most returned product types include **Shorts** and **Helmets**
- Return rate highest for **Road-650 Red, 52**, accounting for 11.1% of category returns

### 🔍 Predictive Drivers (Key Influencers)
- **Marital Status = Married** increases probability of home ownership by 1.62x
- **Higher product cost** is positively correlated with **Average Retail Price**

---

## 🧱 Data Model

The data model uses a classic star schema with relationships between:

- Sales Data ↔ Product, Customer, Calendar, and Territory lookups
- Returns Data as a secondary fact table
- Measure Table for calculated KPIs and DAX metrics

> ![Model View](screenshots/Model%20View.png)

---

## 🖼️ Dashboard Screenshots

| Summary KPI | Customer Detail | Product Performance |
|-------------|------------------|----------------------|
| ![Summary Dashboard](screenshots/SummaryDashboard.png) | ![Customer Detail](screenshots/Customer%20Detail.png) | ![Product Detail](screenshots/Product%20Detail.png) |

| Return Tree | Key Drivers |
|-------------|-------------|
| ![Decomposition Tree](screenshots/Decomposition%20Tree.png) | ![Key Influencers](screenshots/Key%20Influencers.png) |

---

## 🛠️ Tools Used

- **Power BI Desktop** for dashboard building
- **DAX** for calculated measures (e.g. Return Rate, Rolling Revenue, Profit)
- **Star Schema** data modeling
- **Decomposition Tree**, **Key Influencers**, and **Bubble Chart** visuals

---

## 📌 Author

**Sulaiman Yusuf Zakaria**  
Master of Business Analytics – Macquarie University  
Certified: [Microsoft Power BI Desktop for Business Intelligence](https://www.udemy.com/certificate/...)

---

## 📎 License

This project is for educational and portfolio purposes only. Data is based on publicly available AdventureWorks dataset.

