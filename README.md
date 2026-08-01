# International Sales Performance Analysis (2021–2023) 📊

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Excel-217346?style=flat&logo=microsoftexcel&logoColor=white)
![Status](https://img.shields.io/badge/status-active-success)

An interactive Power BI dashboard analyzing global sales and revenue data from 2021 to 2023, built from a dataset of ~1,700 order records spanning multiple regions, countries, and product categories.

![Dashboard Preview](Images/Shipment%20Report%202021%20to%202023.png)

## Overview

This dashboard transforms raw order transaction data: order ID, region, country, item type, sales channel, order priority, units sold, pricing, and cost, into actionable business insights across revenue, cost, and profitability.

### Business Objectives

This analysis was built to answer core commercial questions a sales or finance team would ask when reviewing three years of international order data:

Profitability — How profitable is the business overall, and is that profitability improving or eroding over time?
Regional performance — Which regions and countries generate the most revenue, and do they convert that revenue into profit at the same rate?
Growth trend — Is the business growing year-over-year, and at what rate?
Product mix — Which product categories are the most and least profitable, independent of how much revenue they generate?
Channel effectiveness — Does the online or offline sales channel perform better on revenue and margin?
Seasonality — Are there predictable quarterly patterns in demand that could inform inventory or staffing decisions?
Analysis & Key Findings
### 1. Profitability Overview

Across all 1,700 orders (2021–2023), the business generated R2.25bn in revenue, R1.59bn in cost, and R664.23M in profit — an overall profit margin of 29.5%. The average order value across the full dataset is roughly R1.32M in revenue per order.

### 2. Regional Performance

Sub-Saharan Africa is the largest revenue contributor (R610.2M, ~27% of total revenue), followed by Europe (R561.3M) and the Middle East & North Africa (R306.3M). However, revenue rank and profitability rank don't fully align: Australia and Oceania has the highest profit margin of any region (31.0%) despite generating the least revenue of the major regions, while Europe has the lowest margin (28.8%) among top-performing regions — meaning it moves more volume but retains slightly less of each dollar earned. This suggests regional pricing or cost structures differ meaningfully and are worth investigating individually.

At the country level, Bangladesh stands out — it ranks second by revenue but converts it at a 34.3% margin, the highest among the top 5 revenue-generating countries. Austria leads in raw revenue (R28.4M) but converts at a below-average 29.2% margin.

### 3. Year-over-Year Growth

Revenue grew from R532.4M in 2021 to R599.1M in 2022 (+12.5%), then accelerated sharply to R1.12bn in 2023 (+86.8% year-over-year) — the business roughly doubled in its final year, driven by a jump in order volume (383 → 458 → 859 orders) and units sold (1.89M → 2.34M → 4.23M). Despite this growth, profit margin slipped slightly each year — from 30.4% (2021) to 29.6% (2022) to 29.0% (2023) — indicating that rapid growth came with a modest but consistent erosion in cost efficiency, worth monitoring as the business scales further.

### 4. Product Category Margins

Revenue and profitability tell very different stories by category. Clothes is by far the most profitable category by margin (67.2%), followed by Cereal (43.1%) and Vegetables (41.0%) — despite none of these being top revenue generators. By contrast, Meat (13.6% margin), Office Supplies (19.4%), and Household (24.8%) generate substantial revenue (Household alone brings in R507.9M) but return comparatively little profit per rand of sales. This gap between revenue volume and margin quality is one of the most actionable findings in the dataset.

### 5. Sales Channel Comparison

Offline sales generate more total revenue (R1.22bn vs. R1.03bn online) and a near-identical order count (859 vs. 841), but online orders are marginally more profitable (29.6% margin vs. 29.4% offline) — a small but consistent edge that compounds at scale.

### 6. Seasonality

Units sold show a clear seasonal build within each year — typically lowest in Q1 and rising toward Q3/Q4 — and 2023 in particular shows a sharp step-change upward across all quarters compared to 2021 and 2022, consistent with the acceleration seen in the revenue growth figures above.

## Key Metrics

- **Total Profit:** R664.23M
- **Total Revenue by Region:** Sub-Saharan Africa leads, followed by Europe, the Middle East, Asia, and other regions
- **Total Revenue by Year:** Year-over-year comparison across 2021, 2022, and 2023
- **Revenue vs. Cost Split:** Pie chart breakdown of total revenue against total cost
- **Cost by Item Type:** Top spending categories such as Household, Office Supplies, and Meat
- **Revenue by Country:** Top-performing countries by total revenue (Austria, Bangladesh, Malawi, and more)
- **Units Sold by Quarter:** Quarterly sales volume trends across all three years, highlighting seasonal patterns and growth

## Features

- Multi-panel dashboard combining KPI cards, bar charts, line charts, and pie charts
- Regional and country-level revenue breakdowns
- Time-based trend analysis (yearly and quarterly)
- Cost and profitability analysis by product category

## Tech Stack

- **Power BI** for data visualization and dashboard design
- **Excel** for source data storage and preprocessing

## Data

The dataset (`Excel Data Set/International Sales Performance Analysis (2021–2023).xlsx`) contains order-level records with the following fields:

| Column | Description |
|---|---|
| Order ID | Unique identifier for each order |
| Region | Geographic region of the order |
| Country | Country of the order |
| Item Type | Product category |
| Sales Channel | Online or offline |
| Order Priority | Priority level (L, M, H, C) |
| Order Date | Date the order was placed |
| Units Sold | Quantity of units sold |
| Unit Price | Price per unit |
| Unit Cost | Cost per unit |
| Total Revenue | Units Sold × Unit Price |
| Total Cost | Units Sold × Unit Cost |
| Total Profit | Total Revenue − Total Cost |

### Sample Data

![Sample Data](Images/International%20Sales%20Records.png)

A snapshot of the raw dataset showing individual order records. Each row represents a single order, capturing where it was sold (region, country, channel), what was sold (item type, units, pricing), and the resulting financial outcome (revenue, cost, profit). This transaction-level granularity is what powers the regional, yearly, and category-level breakdowns in the dashboard.

## Setup

1. Clone this repository (it's private, so make sure you're authenticated with GitHub):
   ```bash
   git clone https://github.com/ngcebo100/International-Sales-Performance-Analysis-2021-2023-.git
   ```
2. Open **Power BI Desktop** (download it [here](https://powerbi.microsoft.com/desktop/) if you don't have it).
3. In Power BI, go to **Get Data → Excel** and select `Excel Data Set/International Sales Performance Analysis (2021–2023).xlsx` from the cloned repo.
4. Build or recreate the visuals using the fields described in the [Data](#data) section above, or reference the images in the `Images/` folder for layout guidance.

## How to Use

- Open the workbook in Excel to explore or filter the raw data directly.
- Load the data into Power BI Desktop to interact with the dashboard — filter by region, country, year, or item type to drill into specific segments.
- Use the visuals to compare revenue and profit trends across years and quarters, or identify top/bottom performing countries and product categories.

### Recommendations
Investigate margin erosion: profit margin has declined slightly every year despite revenue nearly doubling — review whether unit costs, discounting, or logistics costs are rising faster than pricing.
Rebalance the product mix: high-revenue, low-margin categories (Meat, Office Supplies, Household) may benefit from cost renegotiation or pricing review, while high-margin categories (Clothes, Cereal, Vegetables) could be prioritized for marketing investment.
Study regional cost structures: Australia and Oceania's outperformance on margin, versus Europe's comparative underperformance, suggests regional cost or pricing strategies worth replicating or correcting.
Lean further into online: with a consistent margin edge over offline, incremental investment in the online channel may yield better returns per rand spent.
