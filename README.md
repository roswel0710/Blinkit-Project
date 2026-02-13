# 📊 Blinkit Sales Analytics Dashboard | Power BI & SQL

[![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?logo=powerbi)](https://powerbi.microsoft.com/)
[![View Dashboard](https://img.shields.io/badge/View-Live%20Dashboard-yellow?logo=powerbi)](https://app.powerbi.com/view?r=eyJrIjoiMzY5ZDdkYTQtNjNlYi00ZDU0LTljOGYtZDRmMzk5YzYwMTU3IiwidCI6ImJjZWYxYWJlLWVjZjgtNDMxNy1iM2FmLTY0NzQ3MmMwM2Y3OSJ9)
[![SQL](https://img.shields.io/badge/SQL-Advanced%20Analytics-blue)](https://www.w3schools.com/sql/)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

---
<img width="2099" height="1197" alt="Screenshot 2026-02-13 115028" src="https://github.com/user-attachments/assets/dd48da83-9994-4fab-8b6c-e32ffd3ca2ae" />

## 📌 Project Overview

This project demonstrates an **end-to-end analytical workflow** using **Advanced SQL and Power BI** to design a production-ready sales analytics dashboard for **Blinkit (Quick Commerce Retail)**.

The focus of this project is to showcase:
- Strong **SQL-based analytical thinking**
- Robust **metric validation and aggregation**
- Professional **Power BI data modelling and DAX**
- Executive-ready **dashboard design and interactivity**

The dashboard converts raw transactional data into a **clear, scalable, and decision-ready BI solution**.

---

## 🎯 Business Objective

To create a **single-page Power BI dashboard** that enables users to:
- Monitor overall sales performance
- Analyse product characteristics and outlet attributes
- Compare performance across outlet types, sizes, and locations
- Interact dynamically with validated KPIs

---

## 🧩 Dashboard Structure

The dashboard follows a **logical analytical flow**:

### 🔹 Interactive Filter Panel
- Outlet Location  
- Outlet Size  
- Item Type  
- Reset Filters option for usability  

---

### 🔹 KPI Summary Section

| KPI | Description |
|---|---|
| **Total Sales** | Aggregate revenue across all outlets |
| **Total Items** | Total number of item records |
| **Average Sales** | Mean sales per item |
| **Average Rating** | Overall customer rating |

All KPIs are built using **explicit DAX measures** to ensure consistency across visuals and filters.

---

## 📈 Visual Analysis Components

- **Sales Trend by Outlet Establishment Year**  
  Area chart highlighting long-term sales progression and peak periods.

- **Fat Content Analysis**  
  Donut charts showing sales distribution by Low Fat vs Regular items.

- **Item Type Performance**  
  Horizontal bar chart ranking product categories by total sales.

- **Outlet Location Analysis**  
  Tier-wise comparison (Tier 1, Tier 2, Tier 3).

- **Outlet Size Contribution**  
  Percentage distribution of Small, Medium, and High outlets.

- **Outlet Type Performance Table**  
  Comparison of Grocery Stores and Supermarket formats using:
  - Total Sales
  - Item Count
  - Average Sales
  - Average Rating
  - Item Visibility  
  Enhanced using conditional formatting.

---

## 🧠 Technical Foundation

### 🔹 SQL (Analytical Layer)

SQL was used as the **primary analytical layer** to:
- Aggregate and validate all KPIs before visualisation
- Perform category-level and outlet-level analysis
- Calculate percentage contribution metrics
- Ensure alignment between backend logic and Power BI measures

Key SQL concepts applied:
- `SUM()`, `AVG()`, `COUNT()`
- `GROUP BY` for multi-dimensional aggregation
- Ordering and ranking logic for category analysis
- Metric validation prior to BI ingestion
- Windows funcion for rank analysis
- CTE's, Sub-queries

---

### 🔹 Power BI & DAX (Semantic Layer)

- Built **explicit DAX measures** for all KPIs to avoid inconsistent implicit aggregations  
- Designed measures to **respect filter context** across slicers and visuals  
- Implemented **percentage contribution measures** for donut charts and outlet size analysis  
- Reused measures across visuals to maintain metric integrity  
- Applied conditional formatting and sorting logic for executive readability  

---

### 🔹 Data Model & Performance

- Clean, simplified data model optimised for aggregation
- Avoided unnecessary calculated columns
- Ensured consistent formatting and naming conventions
- Designed for scalability and performance

---

## 🔑 Key Technical Highlights

- Advanced SQL aggregation and metric validation  
- Strong understanding of **DAX context and measure design**  
- Interactive Power BI dashboard with dynamic filtering  
- Professional KPI structuring and visual hierarchy  
- End-to-end BI workflow from SQL to published dashboard  
- Live dashboard published via **Power BI Service**  

---

## 📂 Repository Structure

```text
├── Blinkit Power BI Dashboard.pbix
├── BLINKIT Analysis.docx
├── README.md
