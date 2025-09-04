# 📊 Excel Sales Forecasting & Performance Dashboard

## Table of Contents
- [Project Objective](#project-objective)  
- [Dashboard Preview](#dashboard-preview)  
- [Data Source](#data-source)  
- [Tools and Features](#tools-and-features)  
- [Key Dashboard Element](#key-dashboard-element)  
- [Methodology](#methodology)  
- [Insights and Recommendations](#insights-and-recommendations)  

---

## Project Objective
To analyze **5 years of retail sales data (2020–2024)** across multiple regions and product categories,  
and create an **interactive Excel dashboard** with a **forecast for 2025 sales**, providing decision-makers with actionable insights.

---

## Dashboard Preview
<img width="747" height="409" alt="Screenshot 2025-09-03 230846" src="https://github.com/user-attachments/assets/7193a3dd-c13a-4b9b-b5c1-2efa16bf9d8d" />

<img width="943" height="491" alt="Screenshot 2025-09-03 231046" src="https://github.com/user-attachments/assets/35144f2d-f9a5-47b7-aedb-6a1c03373042" />



---

## Data Source
- Synthetic dataset created for this project:  
  `dataset/excel_sales_forecasting_dataset.csv`  
- Contains:  
  - **Date** (monthly, 2020–2024)  
  - **Region** (North, South, East, West)  
  - **Product Category** (Electronics, Clothing, Home Appliances, Groceries, Furniture)  
  - **Sales, Expenses, Profit**

---

## Tools and Features
- **Microsoft Excel**  
  - Power Query → Data cleaning & preparation  
  - PivotTables & PivotCharts → Analysis & visualization  
  - Forecast Sheet → Sales forecasting (2025)   

---

## Key Dashboard Element
- KPI Cards → Total Sales, Total Profit, Expenses, Profit Margin  
- Line Chart → Sales & Profit trends (2020–2024)  
- Donut Charts → Regional
- Bar Chart → Category performance  
- Forecast Sheet → Projected 2025 sales  


---

## Methodology
1. Imported and cleaned dataset using Power Query.  
2. Normalized data into **Star Schema tables** (Date, Region, Product, Sales).  
3. Built PivotTables and visualizations for trends and breakdowns.  
4. Created **2025 forecast** using Excel Forecast Sheet.  
5. Designed dashboard layout with interactive Page Navigator  

---

## Insights and Recommendations
- **Seasonality detected:** Sales peak in specific months, useful for inventory planning.  
- **Top regions:** North & South consistently outperform other regions.  
- **High-margin products:** Home Appliances & Furniture contribute the most profit.  
- **At-risk categories:** Groceries shows high expenses and lower profitability.  
- **Forecast:** 2025 sales projected to continue upward trend → Recommendation: invest in top-performing regions and categories while reviewing cost efficiency in underperforming ones.  

---

👨‍💻 Created as part of my **Data Analytics Portfolio**
