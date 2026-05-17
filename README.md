

<p align="center"><i>Track. Analyze. Forecast. Grow.</i></p>

<br>

<p align="center">
  <a href="https://www.linkedin.com/in/shubham-kumar-gupta-a3a125407/">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://github.com/shubzzmk2003-dotcom">
    <img src="https://img.shields.io/badge/GitHub-Follow-black?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  <img src="https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" />
</p>

<br>

<p align="center">
An interactive Power BI dashboard built to analyze SuperStore sales data, track performance metrics, and generate actionable business insights using data visualization and forecasting techniques.
</p>

<br>

---

## 📑 Table of Contents

- [Project Overview](#-project-overview)
- [Business Problem](#-business-problem)
- [Dashboard Preview](#-dashboard-preview)
- [Key Features](#-key-features-of-dashboard)
- [Key Insights](#-key-insights)
- [Sales Forecasting](#-sales-forecasting)
- [DAX Measures Used](#-dax-measures-used)
- [Tools & Technologies](#️-tools--technologies-used)
- [Future Improvements](#-future-improvements)
- [Skills Demonstrated](#-skills-demonstrated)
- [Author](#-author)

<br>

---

## 🚀 Project Overview

The goal of this project is to analyze sales performance, identify key growth drivers, and monitor profitability using interactive dashboards.

<br>

It helps in understanding:

- 📅 Year-wise sales and profit trends
- 🏆 Top-performing products and categories
- 🌍 Regional performance across USA
- 📉 Forecasted sales patterns for next 15 days

<br>

---

## 🧠 Business Problem

Businesses often struggle to:

- ❌ Track real-time sales performance
- ❌ Identify profit-driving segments
- ❌ Understand regional and category trends
- ❌ Forecast future sales accurately

<br>

> ✅ This dashboard solves these problems by transforming raw sales data into clear, visual insights for better decision-making.

<br>

---

## 📷 Dashboard Preview

<br>

### 🏠 Cover Page

<img width="1529" height="845" alt="Cover Page" src="https://github.com/user-attachments/assets/a3eccad7-a565-47c0-912e-3a6beb490b2e" />

<br><br>

### 📊 Dashboard

<img width="1371" height="781" alt="Sales Dashboard" src="https://github.com/user-attachments/assets/ccadf027-a3af-489c-8cc0-7db3bd42fb3a" />

<br><br>

### 📉 Sales Forecasting

<img width="1374" height="774" alt="Sales Forecasting" src="https://github.com/user-attachments/assets/dbfffbfd-0f58-4bf5-a0b4-fe2dcecba771" />

<br><br>

### 🔍 Key Insights

<img width="1376" height="777" alt="Key Insights" src="https://github.com/user-attachments/assets/72589207-16df-4c6b-af18-005da9a9da21" />

<br>

---

## 📌 Key Features of Dashboard

<br>

| Feature | Description |
|---------|-------------|
| 📊 KPI Cards | Sales, Profit, Quantity, Profit Margin |
| 🌍 Regional Map | Visual sales performance across USA |
| 📈 YOY Trends | Year-wise Sales & Profit analysis |
| 📉 Forecasting | 15-day future trend prediction |
| 🧾 Category Insights | Category & Sub-category breakdown |
| 🎯 Filters & Slicers | Interactive dynamic exploration |
| 📦 Quantity Analysis | Formatted value tracking |
| 💰 Profit Margin | Business efficiency analysis |

<br>

---

## 📈 Key Insights

<br>

- ✅ Total sales and profit show **consistent growth trend** over years
- ✅ **Consumer segment** drives **48%** of total sales as primary revenue driver
- ✅ **Office Supplies & Phones** are the strongest performing categories
- ✅ **West region** is the top-performing region across all metrics
- ✅ **Standard Class shipping** accounts for 0.91M in revenue
- ✅ **California** is the top-performing state with 0.34M in sales
- ✅ Profit margin remains a key indicator of business efficiency

<br>

---

## 📉 Sales Forecasting

<br>

- Implemented **time-series forecasting** to predict future sales trends
- Forecast helps in understanding short-term business performance
- Shows expected sales movement based on historical patterns
- Helps in inventory planning and demand estimation
- Provides insights for better business decision-making

<br>

> 📊 The forecast indicates a **stable sales trend with minor fluctuations**, suggesting consistent market demand.

<br>

---

## 📊 DAX Measures Used

<br>

```dax
Total Sales = SUM(Orders[Sales])

Total Profit = SUM(Orders[Profit])

Profit Margin (%) = DIVIDE([Total Profit], [Total Sales], 0) * 100

Total Quantity = SUM(Orders[Quantity])

YOY Growth = 
DIVIDE(
    [Total Sales] - CALCULATE([Total Sales], SAMEPERIODLASTYEAR('Date'[Date])),
    CALCULATE([Total Sales], SAMEPERIODLASTYEAR('Date'[Date])),
    0
)
```

<br>

---

## 🛠️ Tools & Technologies Used

<br>

| Tool | Purpose |
|------|---------|
| ![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black) | Dashboard & Visualization |
| ![Excel](https://img.shields.io/badge/Excel-217346?style=flat&logo=microsoft-excel&logoColor=white) | Data Preparation |
| DAX | Data Analysis Expressions |
| Power Query | Data Cleaning & Transformation |
| Forecasting | Time-Series Sales Prediction |

<br>

---

## 📌 Future Improvements

<br>

- 🔄 Integration with SQL database for real-time updates
- 🤖 Advanced forecasting using ML models
- ⚙️ Automated data refresh pipeline
- 🔍 Drill-through analysis for deeper insights

<br>

---

## 🎯 Skills Demonstrated

<br>

- ✅ Data Cleaning & Transformation
- ✅ Business Intelligence Reporting
- ✅ KPI Design
- ✅ DAX Calculations
- ✅ Forecasting & Trend Analysis
- ✅ Analytical Thinking
- ✅ Data Visualization

<br>

---

## 👨‍💻 Author

<br>

**Shubham Kumar Gupta**
**Shubham Kumar Gupta**
B.Com Final Year Student | Aspiring Data Analyst

<br>

<p align="center">
  <a href="https://www.linkedin.com/in/shubham-kumar-gupta-a3a125407/">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://github.com/shubzzmk2003-dotcom">
    <img src="https://img.shields.io/badge/GitHub-Follow-black?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

<br>

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub and feel free to connect on LinkedIn for collaboration or feedback!

<br>




