# 📊 Sales Performance Dashboard (Power BI)

An interactive, multi-page **Power BI** dashboard analyzing revenue, profitability,
product performance, and customer behavior — built to deliver self-serve insights
for data-driven decision-making.

> **Data Source:** Microsoft *AdventureWorks* sample dataset (a fictional bicycle
> manufacturer), modeled and visualized end-to-end in Power BI Desktop.

![Executive Dashboard](images/dashboard-overview.png)

---

## 🎯 Business Objectives
- Monitor overall revenue, profit, and order performance
- Track KPIs against monthly targets
- Identify top-performing products, regions, and customers
- Analyze customer segmentation and purchasing behavior
- Model price-sensitivity scenarios to support pricing decisions

---

## 🔑 Key Insights
- **$24.9M** total revenue • **$10.5M** profit • **25.2K** orders • **2.2%** return rate
- **Tires and Tubes** is the most-ordered product; **Shorts** the most-returned
- **17.4K** unique customers at **$1,431** average revenue per customer
- Top customer (*Mr. Maurice Shan*) generated **$12.4K** in revenue
- Orders concentrated in the **US**, with secondary demand across Europe and the Pacific

---

## 🗂️ Dashboard Pages

### 1. Executive Overview
High-level KPIs (Revenue, Profit, Orders, Return Rate), revenue-trend analysis,
orders by category, top-10 products by revenue, and month-over-month performance.

### 2. Geographic Analysis
![Map View](images/map-view.png)

Interactive map of sales by region with one-click filters for **Europe**,
**North America**, and **Pacific**.

### 3. Product Analysis
![Product Detail](images/product-detail.png)

Product-level **Orders / Revenue / Profit vs. Target** gauges, a dynamic metric
selector, and a **"Price Adjustment %" what-if parameter** that models Adjusted
Profit under different pricing scenarios.

### 4. Customer Analysis
![Customer Detail](images/customer-detail.png)

Customer segmentation by **income level** and **occupation**, revenue-per-customer
metrics, and a top-100 customers leaderboard.

---

## 🧠 Techniques & Features
- **DAX measures** for KPIs, targets, return rates, and time intelligence
- **What-if parameter** for interactive price-sensitivity / scenario analysis
- **KPI vs. Target gauges** for performance tracking
- **Dynamic metric selection** (disconnected slicer) to switch between measures
- **Drill-through** to product- and customer-detail pages
- **Interactive map** with region-level filtering
- **Data modeling** with star-schema relationships across fact and dimension tables

---

## 🛠️ Tools & Technologies
`Power BI Desktop` · `DAX` · `Power Query` · `Data Modeling`

---

## 🚀 How to Use
1. Download `Sales-Performance-Dashboard.pbix` from this repository
2. Open it in **Power BI Desktop**
3. Interact with the slicers, filters, drill-throughs, and the what-if parameter

---

## 👤 Author
**Krishna Maniyar**
📧 krishnamaniyarkm22@gmail.com · [LinkedIn](https://www.linkedin.com/in/krishnamaniyar/) · [Portfolio](https://krishnamaniyar2209.github.io/)
