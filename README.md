# E-Commerce Sales & Products Analysis — Tableau

> An interactive dual-dashboard system that answers three core business questions: which product categories drive growth, how geography shapes order volume, and where quantity sold and profit margin intersect.

[![Tableau Public](https://img.shields.io/badge/View%20Live%20Dashboard-E97627?style=flat&logo=tableau&logoColor=white)](https://public.tableau.com/views/lab1extract/TotalSalesDachboard?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

---

## Dashboards

### 1. Total Sales Dashboard

![Total Sales Dashboard](Images/tableau%20lab%201.jpg)

A macro-level view of business performance across time, geography, and customer demographics.

| Visual | What it answers |
|--------|----------------|
| KPI summary block | Overall quantity (33,769 units), orders, and margins at a glance |
| Orders per category bar chart | Which of the 5 segments (Electronics, Hardware, Home Appliances, Accessories, Office Supplies) drives the most volume |
| Gender demographic pie chart | 51% male / 49% female — near-equal customer split |
| Monthly orders & final price line chart | Seasonal trends and pricing behavior across the calendar year |
| Avg profit by category | Home Appliances leads in profit margin despite lower order volume than Electronics |
| US geographic sales map | State-level order concentration across CA, TX, NY, and other major markets |

**Filtering:** Category, State, chart type toggle, Show/Hide controls, KPI selector.

---

### 2. Products Analysis Dashboard

![Products Analysis Dashboard](Images/tableau%20lab%202.jpg)

An operational deep-dive into individual product and category performance.

| Visual | What it answers |
|--------|----------------|
| Dynamic Top N products chart | Parameter-driven ranking of highest-volume individual items (Widget AL, Item Z, Tool BA) |
| Category products matrix | Exact order counts broken down by major and sub-category |
| Quantity vs. orders combo chart | Dual-axis view showing where high quantity ≠ high order count — and vice versa |

**Navigation:** Custom synchronized buttons route between the two dashboards for seamless exploration.

---

## Key Insights

- **Volume leader:** Electronics drives the highest absolute order count across all categories.
- **Profit leader:** Home Appliances yields the highest average profit per sale — volume and margin tell different stories.
- **Demographic balance:** A near-50/50 gender split suggests broadly universal product appeal, not a niche audience.

---

## Tools

| Tool | Usage |
|------|-------|
| Tableau Desktop | Dashboard design, calculated fields, parameter controls |
| Mapbox / OpenStreetMap | Geographic map layer |
| Tableau Public | Hosting and sharing |

---

## How to explore

1. Open the [live Tableau Public dashboard](https://public.tableau.com/views/lab1extract/TotalSalesDachboard?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link) in your browser.
2. Use the filter controls at the top to slice by Category, State, or KPI.
3. Toggle between dashboards using the navigation buttons at the top right.
4. Hover over any chart element for detailed tooltips.e dashboard directly in your browser.
