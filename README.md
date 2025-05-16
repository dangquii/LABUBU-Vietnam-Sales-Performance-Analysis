# LABUBU — Vietnam Sales Performance Analysis

A self-service Excel analytics solution that converts raw POS transactions (12 k rows, 3 regions, 30+ stores, 100+ SKUs) into an interactive executive dashboard.  
Managers can slice performance by **region, store, product category, and month** in seconds—no BI license or macros required.

---

## Business question  
> **“How did each region, store, and product line perform this month vs. last month and last year—and which products drove or dragged revenue?”**

---

## What the dashboard delivers

| Insight | Metric | Example (Hà Nội — Sep 2024) |
|---------|--------|-----------------------------|
| **Total revenue** | **$44 041** | ↑ **6.7 % MoM**, ↑ **26.3 % YoY** |
| **Top store** | Big C | **$18 172** revenue, ↑ 27 % MoM |
| **Growth drivers** | Magic Sand | **+$3 294** MoM |
| **Loss drivers** | Rubik’s Cube | **–$2 599** MoM |

> **Result:** Weekly reporting lag eliminated; region managers can rebalance inventory the same day.

---

## Excel techniques showcased

| Purpose | Formula / Feature | Skill demonstrated |
|---------|-------------------|--------------------|
| KPI tiles (Total, MoM, YoY) | `SUMIFS`, `IF`, `INDEX-MATCH` | Conditional aggregation & dynamic period comps |
| Region / Date slicers | Named ranges + `INDIRECT` | Parameter-driven analysis without VBA |
| Dynamic store ranking | `RANK`, `RANK.AVG` | Auto-updating leaderboards |
| Growth / loss tables | Conditional formatting | Instant green/red variance cues |
| Trend mini-chart | Sparklines | Compact YoY vs YTD comparison |

_All formulas are fully documented in the **Analysis** sheet._

---

## Dashboard
! [Dashboard](dashboardlabubu.png)


---

## How to run

1. **Clone** this repo or download the workbook.  
2. Open **LABUBU_VN_Sales_Performance.xlsx** in Excel 365 / 2021.  
3. On the **Dashboard** sheet  
   - Choose a **Region** (green dropdown).  
   - Pick a **Month / Year**.  
   - All KPI tiles, charts and tables refresh via formulas—no macros.  
4. *(Optional)* Replace `data/*.csv` with your own export (same columns) and click **Data ▸ Refresh All**.

---

## Why this project matters

*Rapid insight with just Excel—ideal for SMBs without Power BI/Tableau.*  
*Demonstrates advanced formula engineering, dynamic ranges, and storytelling.*  
*Re-usable: drop any retail dataset into `Data` sheet → get board-ready visuals in minutes.*

---

## About me

**Phu Qui Dang** | _Data Analyst — SQL • Python/pandas • Azure • Excel_  
[LinkedIn](https://www.linkedin.com/in/phu-qui-dang-706bb1218/) | [Portfolio](https://github.com/dangquii)


