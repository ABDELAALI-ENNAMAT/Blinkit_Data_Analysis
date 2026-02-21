<div align="center">

<!-- HEADER BANNER -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=200&section=header&text=🛒%20Blinkit%20Data%20Analysis&fontSize=45&fontColor=fff&animation=twinkling&fontAlignY=35&desc=From%20Raw%20Data%20to%20Real%20Decisions%20—%20A%20Full-Stack%20BI%20Project&descAlignY=55&descSize=16" width="100%"/>

---

<p align="center">
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black"/>
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=python&logoColor=white"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Status-Completed-brightgreen?style=flat-square"/>
  <img src="https://img.shields.io/badge/Dashboard-Live%20on%20Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black"/>
  <img src="https://img.shields.io/badge/Domain-Retail%20%7C%20Grocery%20%7C%20E--Commerce-blue?style=flat-square"/>
  <img src="https://img.shields.io/github/repo-size/ABDELAALI-ENNAMAT/Blinkit_Data_Analysis?style=flat-square&color=orange"/>
</p>

</div>

---

## 🌟 Project Overview

> *"Data is the new grocery — and we just stocked the shelves."*

**Blinkit** (formerly Grofers) is one of India's leading instant grocery delivery platforms. This project is a **comprehensive end-to-end Business Intelligence case study** that transforms raw grocery sales data into actionable insights — using a powerful stack of **SQL, Python, Excel, and Power BI**.

Whether you're a data analyst, hiring manager, or curious developer — this project demonstrates a **real-world BI workflow** from data ingestion to stakeholder-ready dashboards.

---

## 🎯 Project Objective

The core mission of this analysis is to answer **critical business questions** by exploring Blinkit's outlet and product data:

| Question | Business Goal |
|---|---|
| 💰 What drives total revenue? | Maximize sales opportunities |
| 🧈 Does fat content impact buying behavior? | Product health trend analysis |
| 🏪 Which outlet types perform best? | Operational efficiency |
| 📍 Where are the highest-performing outlets? | Geo-targeted marketing |
| 📅 Does outlet age affect performance? | Strategic expansion planning |
| ⭐ What's the customer satisfaction level? | Improve service quality |

---

## 🧰 Tech Stack & Tools

<table>
<tr>
<td align="center" width="120">
<img src="https://img.icons8.com/color/64/microsoft-excel-2019.png" width="48"/><br/>
<b>Excel</b><br/>
<sub>Data exploration & pivot tables</sub>
</td>
<td align="center" width="120">
<img src="https://img.icons8.com/color/64/postgreesql.png" width="48"/><br/>
<b>SQL</b><br/>
<sub>Querying, cleaning, KPI extraction</sub>
</td>
<td align="center" width="120">
<img src="https://img.icons8.com/color/64/python.png" width="48"/><br/>
<b>Python</b><br/>
<sub>EDA with Pandas & Matplotlib</sub>
</td>
<td align="center" width="120">
<img src="https://img.icons8.com/color/64/power-bi.png" width="48"/><br/>
<b>Power BI</b><br/>
<sub>Interactive dashboards & KPIs</sub>
</td>
</tr>
</table>

---

## 📂 Dataset Overview

The dataset is a **real-world grocery retail dataset** from Blinkit, packaged as an Excel workbook (`.xlsx`).

| Field | Description |
|---|---|
| `Item_Fat_Content` | Low Fat / Regular |
| `Item_Identifier` | Unique product code |
| `Item_Type` | Product category (e.g., Fruits, Snacks) |
| `Item_Visibility` | Shelf visibility score |
| `Item_Weight` | Weight of the product |
| `Outlet_Identifier` | Unique outlet code |
| `Outlet_Establishment_Year` | Year the outlet was founded |
| `Outlet_Location_Type` | Tier 1 / Tier 2 / Tier 3 city |
| `Outlet_Size` | Small / Medium / High |
| `Outlet_Type` | Grocery Store / Supermarket Type 1/2/3 |
| `Sales` | Total item revenue |
| `Rating` | Customer satisfaction score |

---

## 📊 KPIs & Business Questions Answered

### 🔢 Core KPIs

```
┌─────────────────────────┬───────────────────────────────────────────────┐
│  KPI                    │  Description                                  │
├─────────────────────────┼───────────────────────────────────────────────┤
│  💵 Total Sales         │  Sum of all item sales across all outlets     │
│  📦 Number of Items     │  Total count of distinct products sold        │
│  📈 Average Sales       │  Mean revenue per item                        │
│  ⭐ Average Rating      │  Mean customer satisfaction score             │
└─────────────────────────┴───────────────────────────────────────────────┘
```

---

### 📌 Granular Business Analysis

#### 🔸 1 · Total Sales by Fat Content
- **Goal**: Does health-conscious labeling affect revenue?
- **Chart**: Donut Chart
- **KPIs**: Total Sales · Avg Sales · Item Count · Avg Rating

#### 🔸 2 · Total Sales by Item Type
- **Goal**: Which product categories are the top revenue drivers?
- **Chart**: Horizontal Bar Chart
- **KPIs**: Sales breakdown per category

#### 🔸 3 · Fat Content Sales Across Outlet Location Types
- **Goal**: How does fat content preference vary by city tier?
- **Chart**: Stacked Column Chart (Low Fat vs Regular by Tier)

#### 🔸 4 · Total Sales by Outlet Establishment Year
- **Goal**: Does outlet age influence performance?
- **Chart**: Line Chart over time

#### 🔸 5 · Sales by Outlet Size
- **Goal**: Small vs Medium vs Large — who wins?
- **Chart**: Pie / Donut Chart

#### 🔸 6 · Sales by Outlet Location Type
- **Goal**: Tier 1 vs Tier 2 vs Tier 3 geographic performance
- **Chart**: Funnel Map

#### 🔸 7 · All KPIs by Outlet Type
- **Goal**: Full performance matrix across all outlet types
- **Chart**: Matrix / Table Card

---

## 🗄️ SQL Analysis Pipeline

The SQL script (`BlinkIt_SQL.sql`) follows a **3-phase analytical pipeline**:

```
Phase 1 → Database Setup & Data Ingestion
Phase 2 → Data Cleaning & Standardization
Phase 3 → KPI Extraction & Business Queries
```

**Sample Query — Sales % by Outlet Size:**
```sql
SELECT
    Outlet_Size,
    CAST(SUM(Sales) AS DECIMAL(10,2)) AS Total_Sales,
    CAST((SUM(Sales) * 100.0 / SUM(SUM(Sales)) OVER()) AS DECIMAL(10,2)) AS Sales_Percentage
FROM BLINKIT
GROUP BY Outlet_Size
ORDER BY Total_Sales DESC;
```

**Sample Query — Full KPI Matrix by Outlet Type:**
```sql
SELECT Outlet_Type,
    CAST(SUM(SALES) AS DECIMAL(10,2))            AS TOTAL_SALES,
    CAST(AVG(SALES) AS DECIMAL(10,1))            AS Average_SALES,
    COUNT(*)                                      AS NUMBER_OF_ITEMS,
    CAST(AVG(Rating) AS DECIMAL(10,2))           AS Average_Rating,
    CAST((SUM(Sales)*100.0/SUM(SUM(Sales)) OVER()) AS DECIMAL(10,2)) AS Sales_Pct
FROM BLINKIT
GROUP BY Outlet_Type
ORDER BY TOTAL_SALES DESC;
```

---

## 🐍 Python EDA Highlights

Using **Pandas** and **Matplotlib** inside `Blinkit Analysis.ipynb`:

- ✅ Null value detection and imputation
- ✅ Duplicate record removal
- ✅ Fat content standardization (`LF` → `Low Fat`, `reg` → `Regular`)
- ✅ Grouped aggregations for sales and ratings
- ✅ Correlation heatmaps
- ✅ Distribution plots for item weights, visibility, and sales

---

## 📈 Excel Workflow

- 🔎 Initial data profiling and quality checks
- 📊 Pivot tables for quick metric summaries
- ✅ Cross-verification of KPIs before Power BI import
- 🧮 Manual formula-based checks for Total Sales & Average Rating

---

## 🖥️ Power BI Dashboard

The Power BI dashboard (`Blinkit Dashboard _july.pbix`) is the **crown jewel** of this project — built with a full multi-page report featuring:

- 🏠 **Home** — Navigation hub
- 📊 **Overview** — High-level KPIs & summary
- 💰 **Sales Overview** — Revenue deep-dive
- 📦 **Inventory** — Product & category analysis
- 📣 **Marketing** — Fat content & location trends
- 👥 **Customer** — Ratings & satisfaction analysis
- 💬 **Feedbacks** — Customer feedback breakdown

### 🖼️ Dashboard Preview

| Page | Screenshot |
|------|-----------|
| 🏠 Home | ![Home](Dashboard%20Images/Home.JPG) |
| 📊 Overview | ![Overview](Dashboard%20Images/Overview.jpg) |
| 💰 Sales Overview | ![Sales Overview](Dashboard%20Images/Sales%20Overview.jpg) |
| 📦 Inventory | ![Inventory](Dashboard%20Images/Inventory.jpg) |
| 📣 Marketing | ![Marketing](Dashboard%20Images/Marketing.jpg) |
| 👥 Customer | ![Customer](Dashboard%20Images/Customer.jpg) |
| 💬 Feedbacks | ![Feedbacks](Dashboard%20Images/Feedbacks.jpg) |

---

## 🚀 Live Dashboard — Try It Now!

> **Experience the full interactive Power BI report live in your browser:**

<div align="center">

[![🚀 Open Live Dashboard](https://img.shields.io/badge/🚀%20Open%20Live%20Dashboard-Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://app.powerbi.com/reportEmbed?reportId=5eda7f4b-1680-429c-a903-01fe85efd64e&autoAuth=true&ctid=2e589d81-ea7a-4dc7-8fb2-84ba95cc947f)

</div>

> 💡 **Note**: The dashboard is hosted on Power BI Service. You may need a Microsoft/Power BI account to view it. Alternatively, download the `.pbix` file from this repository and open it with **Power BI Desktop** (free).

---

## 📁 Repository Structure

```
📦 Blinkit_Data_Analysis/
│
├── 📊  Blinkit Dashboard _july.pbix     ← Full Power BI report
├── 🐍  Blinkit Analysis.ipynb           ← Python EDA notebook
├── 🗄️  BlinkIt_SQL.sql                  ← Full SQL analysis script
├── 📈  BlinkIT Grocery Data.xlsx        ← Raw dataset
├── 📁  Dashboard Images/                ← Dashboard screenshots
│   ├── 🏠  Home.JPG
│   ├── 📊  Overview.jpg
│   ├── 💰  Sales Overview.jpg
│   ├── 📦  Inventory.jpg
│   ├── 📣  Marketing.jpg
│   ├── 👥  Customer.jpg
│   └── 💬  Feedbacks.jpg
└── 📄  README.md                        ← You are here!
```

---

## 🔑 Key Insights & Takeaways

> Here's what the data told us 👇

- 🛒 **Supermarket Type 1** outlets dominate in both total sales and item count
- 🧈 **Low Fat** products slightly outperform Regular in certain outlet tiers — reflecting health trends
- 🏙️ **Tier 3 cities** surprisingly show competitive sales, suggesting untapped potential
- 📅 **Outlets established in 2018** peak in revenue — ideal for benchmarking expansion
- 🏪 **Medium-sized outlets** generate the highest proportion of total revenue
- ⭐ Customer **average rating hovers around 4.0**, indicating strong but improvable satisfaction
- 📦 **Fruits, Vegetables & Snack Foods** are top-selling categories by item count

---

## 🙋‍♂️ About the Author

<div align="center">

**ABDELAALI ENNAMAT**
*Data Analyst | BI Developer | SQL & Python Enthusiast*

[![GitHub](https://img.shields.io/badge/GitHub-ABDELAALI--ENNAMAT-181717?style=for-the-badge&logo=github)](https://github.com/ABDELAALI-ENNAMAT)

</div>

---

<div align="center">

⭐ **If this project added value to you, please consider starring the repo!** ⭐

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" width="100%"/>

</div>