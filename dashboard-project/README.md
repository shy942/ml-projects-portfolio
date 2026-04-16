# 📊 Superstore Sales Dashboard (Power BI)

## 📌 Project Overview

This project presents an **interactive Power BI dashboard** built using the Superstore dataset. The dashboard provides insights into **sales performance, profit trends, and forecasting**, helping stakeholders make data-driven decisions.

---

## 🎯 Objectives

* Analyze **sales and profit trends over time**
* Compare performance across **years, months, and categories**
* Identify **high-performing and low-performing segments**
* Implement **time-series forecasting (next 30 days)**

---

## 📁 File Included

* `SuperstoreDashboard.pbix` → Main Power BI report file

---

## 📊 Key Features

### 1. Sales & Profit Analysis

* Total Sales and Profit KPIs
* Monthly sales trends
* Category and sub-category breakdown

### 2. Time-Based Insights

* Year-wise and month-wise comparisons
* Interactive **Year slicer**
* Drill-down using date hierarchy

### 3. Forecasting

* **30-day sales forecast**
* Confidence interval visualization
* Trend analysis using time-series data

### 4. Interactive Dashboard

* Dynamic filtering using slicers
* Cross-filtering across visuals
* Clean and user-friendly layout

---

## 🛠️ Tools & Technologies

* Power BI
* DAX (Data Analysis Expressions)
* Data Modeling
* Time Series Forecasting (built-in Power BI analytics)

---

## 📈 Example Insights

* Seasonal trends in sales performance
* Profitability differences across categories
* Future sales projections for decision-making

---

## 🚀 How to Use

1. Open the `.pbix` file in Power BI Desktop
2. Explore the dashboard using:

   * Filters (Year, Category, Region)
   * Interactive visuals
3. View forecast trends in the time-series chart

---

## 💡 Key DAX Measures

```DAX
Total Sales = SUM(Sales[Amount])

Profit = SUM(Sales[Revenue]) - SUM(Sales[Cost])
```

---

## 🔥 Future Improvements

* Add customer segmentation analysis
* Integrate advanced forecasting (Python/ARIMA)
* Include KPI alerts and thresholds

---

## 📌 Author

Shamima Yeasmin

---

## ⭐ Notes

This project is designed for:

* Data Analyst portfolio
* Power BI practice
* Business intelligence demonstration

---
