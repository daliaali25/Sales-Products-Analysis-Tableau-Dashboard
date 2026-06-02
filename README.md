# E-Commerce Sales & Products Performance Tableau Dashboard

An interactive, dual-dashboard Tableau project designed to analyze e-commerce retail data. This project delivers actionable insights into total sales performance, customer demographics, geographic distributions, and granular product-level metrics to drive strategic decision-making.

---

## 📊 Project Overview

interactive Sales &amp; Product Analysis Dashboard built with Tableau. 
​The goal wasn’t just to visualize numbers, but to create a tool that answers critical business questions: - ​Which product categories are driving our growth? - ​How do geographic trends impact our order volume? - ​Where is the sweet spot between quantity sold and average profit?

### Key Objectives:
*   Track KPI Metrics: Monitor overall quantity, total orders, and average profit margins.
*   Analyze Customer Demographics: Breakdown sales distribution by gender and location.
*   Optimize Product Portfolio: Identify top-performing items and structural category expansions.
*   Trend Identification: Trace monthly sales and order behavior across the calendar year.



🔗 [View Interactive Dashboard on Tableau Public](https://public.tableau.com/views/lab1extract/TotalSalesDachboard?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

---

## 🖥️ Dashboard Architecture

### 1. Total Sales Dashboard
This macro-view dashboard focuses on high-level operational metrics, geographic distributions, and temporal trends.

![Total Sales Dashboard](Images/tableau%20lab%201.jpg)

*   KPI Summary Block: Dynamic display tracking overall performance metrics (e.g., Total Quantity: 33,769).
*   Orders Per Category: Bar chart highlighting total orders driven by primary sectors (Electronics, Hardware, Home Appliances, Accessories, Office Supplies).
*   Gender Demographics: Clear pie chart analyzing customer gender distribution (51% Male vs 49% Female).
*   Orders Per Month: A continuous dual/line trend tracking Final Price and order behavior across the months of the year.
*   Avg Profit by Category: Granular insights into which product segments net the highest financial returns (led by Home Appliances).
*   Geographic Sales Map: Filled US interactive map tracking localized orders and volumes across major states (CA, TX, NY, etc.).
*   Advanced Filtering: Top-level parameters for Category, State, Chart type toggles, Show/Hide controls, and KPI selections.

---

### 2. Products Analysis Dashboard
An operational deep-dive dashboard designed to drill down into product performance and inventory metrics.

![Products Analysis Dashboard](Images/tableau%20lab%202.jpg)

*   Dynamic Top N Products: Parameter-driven bar chart showing the highest volume individual items (e.g., Widget AL, Item Z, Tool BA) with custom threshold controls.
*   Category Products Expand: A structured matrix view detailing exact order counts across major and sub-categories.
*   Quantity/Orders per Category: A dual-axis combined bar and line chart visualizing the relationship between bulk quantities sold and absolute order count volume.

---

## 🛠️ Tools & Technologies Used

*   Data Visualization: Tableau Desktop
*   Mapping Technology: Mapbox / OpenStreetMap integrations
*   Design Elements: Custom synchronized navigation buttons (*"To Total Sales Analysis"* / *"To Products Analysis Dashboard"*) for seamless UX.

---

## 💡 Key Insights Captured

*   Top Category Driver: Electronics consistently drives the highest absolute volume of orders.
*   Profitability vs. Volume: While Electronics leads in volume, Home Appliances yields the highest Average Profit margin per sale.
*   Demographic Balance: Customer retention and buying habits show a nearly equal split between male and female demographics.

---

## 🚀 How to Interact with the Dashboard

1. Click the [Tableau Public Link](https://public.tableau.com/views/lab1extract/TotalSalesDachboard?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link) at the top of this page to interact with the live dashboard directly in your browser.