# 🛒 Superstore Sales Analysis & Dashboard

> **End-to-end Excel data analysis project** — from raw CSV to interactive sales dashboard

![Excel](https://img.shields.io/badge/Tool-Excel-217346?style=flat-square&logo=microsoft-excel&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-success?style=flat-square)

---

## 📌 Project Overview

This project involves a complete data analysis workflow on the **Superstore Sales Dataset** — a real-world retail dataset containing **3,959 orders** across 4 years (2015–2018). Starting from a raw CSV file, the project covers data cleaning, multi-dimensional pivot table analysis, and a fully interactive Excel dashboard.

---

## 🎯 Objectives

- Clean and standardize raw sales data
- Analyze performance across multiple dimensions (region, category, year, segment)
- Identify top-performing products, states, and customer segments
- Deliver an interactive dashboard for executive reporting

---

## 📂 Dataset

| Column | Description |
|--------|-------------|
| Row ID | Unique row identifier |
| Order ID | Unique order identifier |
| Order Date | Date the order was placed |
| Ship Date | Date the order was shipped |
| Ship Mode | Shipping method |
| Customer ID / Name | Customer info |
| Segment | Consumer / Corporate / Home Office |
| Country / City / State | Location data |
| Product ID / Name | Product info |
| Category / Sub-Category | Product classification |
| Sales | Revenue per line item |

**Size:** 3,959 rows × 18 columns | **Period:** 2015–2018

---

## 🔧 What Was Done

### 1. Data Cleaning
- Imported raw CSV into Excel
- Standardized date formats — added `Order Date Clean` column for accurate time-series analysis
- Fixed inconsistent formatting across columns

### 2. Pivot Table Analysis (10+ Tables)

| Analysis | Insight |
|----------|---------|
| Sales by Year | Growth trend 2015 → 2018 |
| Sales by Region | West led, South lagged |
| Sales by Category | Technology 38.3% · Furniture 32.7% · Office Supplies 29% |
| Sales by Segment | Consumer highest at ~49% |
| Sales by Ship Mode | Standard Class dominant |
| Sales by State | California #1 ($176K+) |
| Top Customers | By order count and revenue |
| Monthly Trends | Seasonal patterns identified |
| Profit Margin by Category | Technology most profitable |
| Sub-Category Analysis | Phones & Chairs top sub-categories |

### 3. Dashboard
- Interactive dashboard with slicers for Year, Region, Category
- Dynamic charts updating on filter selection
- KPI cards: Total Sales · Top Region · Top Category

---

## 📊 Key Findings

- 📈 **Orders grew** from 783 (2015) to 1,304 (2018) — **66% increase**
- 🖥️ **Technology** leads with **38.3%** of total sales share
- 🗺️ **California** is the top-performing state with **$176,044** in sales
- 👥 **Consumer segment** accounts for nearly **50%** of all orders
- 🚢 **Standard Class** shipping is used in **58%** of all orders

---

## 📁 Files in This Repository

```
superstore-sales-analysis/
│
├── README.md
├── data/
│   └── train_read_only.csv          # Raw dataset
└── final_mohamed_ezzat.xlsx         # Cleaned data + pivot tables + dashboard
```

---

## 🚀 How to Open

1. Download `final_mohamed_ezzat.xlsx`
2. Open in **Microsoft Excel** (2016 or later recommended)
3. Navigate to the **Dashboard** sheet
4. Use slicers to filter by Year / Region / Category

---

## 👤 Author

**Mohamed Ezzat Anwar** — Data Analyst  
📧 mhmdezzat24@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/mohamedezzat222/)
