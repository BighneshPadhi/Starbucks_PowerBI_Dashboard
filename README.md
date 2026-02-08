# ☕ Starbucks Sales Analysis Dashboard (Power BI)

A data analytics and visualization mini-project built using **Microsoft Power BI** to analyze Starbucks India sales data and extract actionable business insights through interactive dashboards.

---

## 📌 Project Overview

Starbucks generates large volumes of transactional data across multiple product categories and time periods. The challenge is to transform this raw data into meaningful insights that support strategic decision-making.

This project focuses on building a **dynamic, interactive sales dashboard** that highlights revenue trends, customer behavior, product performance, and peak sales patterns.

---

## 🎯 Aim

To implement a **real-world Data Analytics and Visualization (DAV) problem** using Power BI and present insights through effective visual storytelling.

---


## 🧠 Problem Statement

Transform raw Starbucks transactional data into an interactive dashboard that enables analysis of:
- Sales trends over time
- Product category performance
- Customer purchasing behavior
- Revenue and quantity insights

---

## 🛠️ Methodology

### 1️⃣ Data Preparation
- Cleaned and transformed datasets using **Power BI Power Query**
- Merged:
  - `Orders_Table.csv`
  - `Products_Table.csv`
- Created derived columns (Month, Day, Hour)

### 2️⃣ Data Modeling
- Built relationships between tables using Product ID
- Optimized model for reporting

### 3️⃣ DAX Measures
Created custom measures for:
- Total Revenue
- Total Quantity Sold
- Average Orders per Person
- Average Price per Person

### 4️⃣ Visualization
- Designed interactive visuals
- Added slicers for dynamic filtering

---

## 🔄 Project Flow

Raw Data (Orders + Products CSVs)
↓
Power Query Editor (Cleaning & Transformation)
↓
Data Modeling (Relationships)
↓
DAX Measures (KPIs)
↓
Interactive Power BI Dashboard


---

## 💻 Tools & Technologies

- **Microsoft Power BI Desktop**
- **Microsoft Excel** (optional preprocessing)

---

## 📊 Dashboard Insights

### 🔢 Key Metrics
- **Total Revenue:** ₹70.6M  
- **Total Quantity Sold:** 243K  
- **Average Orders per Person:** 1  
- **Average Spend per Person:** ₹473.4  

---

### ⏰ Sales Timing Trends
- **Peak Hours:** 8 AM – 11 AM  
- **Best Sales Day:** Friday  
- **Strong Days:** Tuesday to Saturday  
- **Top Month:** June (steady growth from Jan–Jun)

---

### ☕ Product Performance

**Top Categories by Quantity**
1. Coffee  
2. Tea  
3. Bakery  

**Top Revenue Generator**
- Coffee (₹20M+)

Coffee dominates both **sales volume and revenue**, making it the most valuable category.

---

## 📈 Visuals Used

- KPI Cards
- Line Charts (Hourly, Daily, Monthly Sales)
- Column Charts (Revenue & Quantity by Category)
- Interactive Slicers:
  - Product Category
  - Product Type
  - Month
  - Day of Week

---

## 🧰 DAV Operations Performed

- Data Cleaning (Power Query)
- Feature Extraction (Day, Month, Hour)
- Slicing & Dicing
- Aggregations using DAX
- Visual Analysis using charts and KPI cards
- Interactive filtering using slicers

---


## 🚀 How to View the Dashboard (Mac / Any OS)

Since Power BI Desktop is Windows-only:
1. Publish the `.pbix` file using a Windows system
2. View the dashboard via **Power BI Service**  
   👉 https://app.powerbi.com

---

## 📚 References

- Microsoft Power BI Documentation  
  https://docs.microsoft.com/en-us/power-bi/
- Starbucks India Dataset – Kaggle

---

## ✨ Conclusion

This project demonstrates how real-world sales data can be transformed into meaningful insights using Power BI. The dashboard enables decision-makers to quickly identify trends, optimize product strategy, and understand customer behavior through interactive visual analytics.
