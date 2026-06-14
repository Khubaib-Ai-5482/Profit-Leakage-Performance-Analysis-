# 📊 Profit Leakage & Performance Analysis

---

## 📌 Project Overview

This project is a **Power BI case study** focused on identifying profit leakage and analyzing business performance using a single sales dataset.

The goal was to understand:

* Where the business is losing money
* Which areas are most profitable
* What operational factors are affecting performance

---

## ❗ Problem Statement

The business appeared profitable overall, but deeper analysis revealed hidden inefficiencies.

Main issues:

* Increasing loss over time
* High discount impact on margins
* Certain regions performing poorly
* Specific products generating consistent losses
* Shipping methods affecting profitability

👉 Core problem:
**Revenue is increasing, but profit efficiency is not optimized.**

---

## 📂 Dataset Information

* Total Sales: $13M
* Total Profit: $1.47M
* Total Loss: $920.36K
* Time Period: 2011–2014

The dataset contained a single sales table including:

* Order details
* Region
* Category & Sub-category
* Segment
* Shipping mode
* Sales, Profit, Discount

---

## 🛠️ Tools Used

* Power BI (Dashboard & Visualization)
* Power Query (Data Cleaning)
* DAX (Measures & KPIs)

---

## 🔄 Approach

### 1. Data Cleaning

* Removed inconsistencies in category and region fields
* Standardized naming structure
* Verified numerical accuracy for sales and profit

### 2. Data Modeling

Since dataset was single-table, relationships were not complex. Focus was on:

* Creating calculated measures
* Building hierarchy views (Region → Category → Sub-category)

### 3. DAX Measures Created

* Total Sales
* Total Profit
* Total Loss
* Profit Margin %
* Loss Contribution %
* Year-wise Trend Measures

### 4. Dashboard Development

Two main dashboards were created:

* Profit Leakage Analysis Dashboard
* Performance Overview Dashboard

---

## 📊 Key Insights

### 🌍 Regional Performance

* Central region shows highest profit and highest loss simultaneously
* Indicates inconsistent order-level control

---

### 📉 Loss Trend

* Loss increased continuously from 2011 to 2014
* Suggests structural inefficiencies were not fixed over time

---

### 📦 Category Analysis

* Technology contributes the highest loss share
* Office Supplies performs relatively better

---

### 🚚 Shipping Mode Impact

* Same Day shipping has lowest profitability
* Standard Class is most efficient and stable

---

### 👥 Segment Analysis

* Consumer segment is the biggest source of loss
* Corporate and Home Office segments are more stable

---

### 📦 Sub-category Issues

Major loss contributors:

* Tables
* Bookcases
* Phones
* Chairs

👉 Small number of products responsible for large portion of losses

---

## 📊 Final Dashboard (Power BI)

The dashboard includes:

### ✔ Profit Leakage View

* Total Profit vs Loss vs Sales
* Region-wise performance
* Category & Sub-category breakdown
* Year-wise trend analysis

### ✔ Performance View

* Profit by region
* Shipping mode impact
* Segment-wise profitability
* Category contribution analysis

---

## 💡 Business Recommendations

### 1. Control Discounts

Introduce strict discount rules, especially for Consumer segment.

---

### 2. Optimize Products

Focus on loss-making products:

* Tables
* Bookcases

Reprice or remove them if needed.

---

### 3. Improve Shipping Strategy

* Limit Same Day delivery
* Promote Standard Class shipping
* Introduce minimum order conditions

---

### 4. Region Monitoring

Central region requires deep-level monitoring at order level.

---

### 5. Product-Level Analysis

Shift from category-level to SKU-level decision making for better accuracy.

---

## 🏁 Conclusion

This project shows that although the business is growing in sales and profit, there is a hidden inefficiency causing nearly **$920K in profit leakage**.

The key learning is:

> Growth without control leads to hidden losses.

With proper optimization in discounts, shipping, and product strategy, the business can significantly improve profitability and reduce losses.

---

## 🚀 Skills Demonstrated

* Power BI Dashboarding
* Data Cleaning & Transformation
* DAX Calculations
* Business Insight Generation
* KPI Analysis
* Data Storytelling

---

## 📌 Outcome

Converted raw sales data into actionable business insights using Power BI, enabling clear identification of profit leakage areas and optimization opportunities.
