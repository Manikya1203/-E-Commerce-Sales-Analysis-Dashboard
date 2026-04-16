# 🛒 E-Commerce Sales Analysis Dashboard

<div align="center">
<!-- Header Banner -->
<img width="1892" height="683" alt="HOMEPAGE" src="https://github.com/user-attachments/assets/dd945544-fd09-46f9-9c2c-9449ebd0edc9" />

<br/>

![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Data Analysis](https://img.shields.io/badge/Data_Analysis-CC0000?style=for-the-badge&logo=databricks&logoColor=white)
![Dashboard](https://img.shields.io/badge/Dashboard-1a1a1a?style=for-the-badge&logo=tableau&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)
![Dashboard Banner](https://img.shields.io/badge/E--Commerce-Sales%20Analysis-00bcd4?style=for-the-badge&logo=shopify&logoColor=white)
![Year](https://img.shields.io/badge/Year-2026-blue?style=for-the-badge)

**A fully interactive multi-page Power BI dashboard for end-to-end e-commerce sales performance analysis — featuring KPIs, trends, profit insights, geographic distribution, and AI-driven business recommendations.**

</div>

---

## 📑 Table of Contents

- [Overview](#-overview)
- [Pages](#-pages)
- [KPI Metrics](#-kpi-metrics)
- [Visualizations](#-visualizations)
- [Insights & Recommendations](#-insights--recommendations)
- [Tech Stack](#-tech-stack)
- [How to Use](#-how-to-use)
- [Project Structure](#-project-structure)
- [Author](#-author)

---

## 🌐 Overview

This dashboard provides a **360° view of e-commerce sales performance**, designed to help business analysts, managers, and stakeholders make data-driven decisions. It covers everything from high-level KPI tracking to granular category-level profit analysis and AI-generated strategic recommendations.

> 🎯 **Goal:** Turn raw sales data into clear, actionable intelligence — from total revenue down to which products are silently eating your margin.

---

## 📄 Pages

### `1` 🏠 Home Page
The **navigation hub** of the report. Users are greeted with a clean welcome screen offering two primary paths:
<img width="1856" height="658" alt="HOMEPAGE" src="https://github.com/user-attachments/assets/936f3d61-fcd2-4ab0-90cd-f0a852468dc6" />

| Tile | Description |
|------|-------------|
| 💡 **DASHBOARD** | Sales overview, KPIs, top products & analytical performance |
| 📘 **INSIGHTS** | Trends, alerts, profit analysis & growth opportunities |

> Signed-in user profile displayed at the top right corner with status indicator.

---

### `2` 📊 Dashboard Page
The core analytical view with **filters, KPI cards, and 6 chart types**.
<img width="1861" height="657" alt="DASHBOARD" src="https://github.com/user-attachments/assets/1ccb98f0-b93e-4caa-b0e7-99dbd391f95c" />


#### 🎛️ Active Filters
| Filter | Options |
|--------|---------|
| 🌍 Region | Central · East · South · West |
| 🚚 Ship Mode | First Class · Same Day · Second Class · Standard Class |

---

## 📈 KPI Metrics

> All KPIs reflect **Year-over-Year (YOY)** growth performance.

| Metric | Value | YOY Growth | Status |
|--------|-------|-----------|--------|
| 💰 **Sales** | $2,297,200.86 | ▲ 20.62% | ✅ Positive |
| 📦 **Profit** | $286,397.02 | ▲ 14.41% | ✅ Positive |
| 🔢 **Quantity** | 37,873 units | ▲ 27.45% | ✅ Positive |
| 🧾 **Orders** | 9,994 | ▲ 28.64% | ✅ Positive |
| 📉 **Profit Margin** | 12.47% | ▼ 5.15% | 🔴 Alert |

> ⚠️ **Critical:** While volume metrics are growing, **Profit Margin is declining** — indicating rising costs or over-discounting.

---

## 📊 Visualizations

### 📅 Monthly Sales & Profit Trend
A dual-axis combo chart tracking monthly Sales (bar) and Profit (line) across the full year.

```
Peak Period:  Sep → Dec (Sales spike to $300K+)
Profit Peak:  Aligned with Q4 but margin compression visible
```

---

### 🍩 Sales Distribution by Category

| Category | Share |
|----------|-------|
| 🖥️ Technology | 32% |
| 🗂️ Office Supplies | 37% |
| 🪑 Furniture | 31% |

---

### 📦 Profit by Category

| Category | Profit | Notes |
|----------|--------|-------|
| 🖥️ Technology | $145,450 | 🏆 Highest profit — most efficient category |
| 🗂️ Office Supplies | $122,490 | Solid performer |
| 🪑 Furniture | $18,450 | ⚠️ Low return for 31% of sales |
| **Grand Total** | **$286,400** | |

---

### 👥 Top 5 Customers by Revenue

| Rank | Customer | Revenue |
|------|----------|---------|
| 🥇 | Sean Miller | $25,040 |
| 🥈 | Tamara Chand | $19,050 |
| 🥉 | Raymond Buch | $15,120 |
| 4️⃣ | Tom Ashbrook | $14,600 |
| 5️⃣ | Adrian Barton | $14,470 |

---

### 🛍️ Best Selling Products by Quantity

| Rank | Product | Units Sold |
|------|---------|-----------|
| 🏆 | **Staples** | 876 |
| 2 | Avery Non-Stick Binders | 74 |
| 3 | Storex Dura Pro Binders | 71 |
| 4 | KI Adjustable-Height Table | 71 |
| 5 | GBC Premium Transparent Covers | 67 |

---

### 🗺️ Geographic Sales Distribution
Interactive US map showing sales heat by state. West region dominates with up to **$457.69K** in sales.

---

## 💡 Insights & Recommendations

> The **Insights Page** delivers 7 color-coded strategic alerts generated from the data.
<img width="1862" height="665" alt="INSIGHTS" src="https://github.com/user-attachments/assets/afdb7c78-e9d2-4ac9-b503-6af88451363e" />


### 🔴 Critical Issues

| # | Alert | Finding | Action |
|---|-------|---------|--------|
| 1 | 🚨 **Profit Margin Declining** | Sales +20.62% but margin fell 5.15% YOY | Fix pricing or renegotiate supplier costs immediately |
| 2 | 📅 **Q4 is Your Peak — You're Not Ready** | Sep–Dec sales spike to $300K+ but margin is shrinking | Plan pricing & inventory before Q4 rush |

---

### 🟡 Opportunities

| # | Insight | Detail |
|---|---------|--------|
| 3 | 🏆 **Technology Is Your Goldmine** | $145K profit = 51% of total profit at only 32% sales volume | Push more ad spend & inventory into Tech |
| 4 | 🪑 **Furniture Is a Problem** | $18.4K profit despite 31% sales mix | Reprice it or cut low-margin SKUs |
| 5 | 📌 **Staples Is Misleading** | 876 units sold — high volume, but is it profitable? | Verify margin contribution vs. order inflation |

---

### 🟢 Strategic Alerts

| # | Alert | Recommendation |
|---|-------|----------------|
| 6 | 👥 **Top 5 Customers = Risky Concentration** | Sean Miller alone = $25K | Launch a loyalty/retention program now |
| 7 | 🌍 **West Dominates, South Lags** | South significantly behind all regions | Run targeted South campaign or investigate demand |

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| 


## 🚀 How to Use

```bash
# 1. Clone this repository
git clone https://github.com/your-username/ecommerce-sales-dashboard.git

# 2. Open the Power BI file
cd ecommerce-sales-dashboard
start ECommerce_Sales_Dashboard.pbix   # Windows
open ECommerce_Sales_Dashboard.pbix    # Mac (requires Power BI Desktop)
```

### Steps Inside Power BI

```
1. Open the .pbix file in Power BI Desktop
2. Update the data source path (Transform Data → Data Source Settings)
3. Click Refresh to load your data
4. Navigate: Home Page → Dashboard or Insights
5. Use Region & Ship Mode filters to slice the data
```

---

## 📁 Project Structure

```
📦 ecommerce-sales-dashboard
 ┣ 📊 ECommerce_Sales_Dashboard.pbix   ← Main Power BI file
 ┣ 📂 data/
 ┃ ┗ 📄 sales_data.csv                 ← Raw data source
 ┣ 📂 screenshots/
 ┃ ┣ 🖼️ HOMEPAGE.png
 ┃ ┣ 🖼️ DASHBOARD1.png
 ┃ ┗ 🖼️ INSIGHTS.png
 ┗ 📄 README.md
```

---

## 👤 Author

<div align="center">

| | |
|---|---|
| 👤 **Name** | Manikya |
| 📊 **Project** | E-Commerce Sales Analysis Dashboard |
| 📅 **Year** | 2026 |

</div>

---

<div align="center">

⭐ **If you found this useful, please star the repo!**

![Footer](https://img.shields.io/badge/E--Commerce%20Sales%20Analysis%20Dashboard-2026-00bcd4?style=for-the-badge)

</div>
