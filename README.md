# International Sales Performance Analysis (2021–2023) 📊

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Excel-217346?style=flat&logo=microsoftexcel&logoColor=white)
![Status](https://img.shields.io/badge/status-active-success)

An interactive Power BI dashboard analyzing global sales and revenue data from 2021 to 2023, built from a dataset of ~1,700 order records spanning multiple regions, countries, and product categories.

![Dashboard Preview](Images/Shipment%20Report%202021%20to%202023.png)

## Overview

This dashboard transforms raw order transaction data — order ID, region, country, item type, sales channel, order priority, units sold, pricing, and cost — into actionable business insights across revenue, cost, and profitability.

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

## Power BI Template

The full interactive dashboard is available as a Power BI template file: [`International_Sales_Performance_Analysis_2021-2023.pbit`](Excel%20Data%20Set/International_Sales_Performance_Analysis_2021-2023.pbit)

This template contains the pre-built report — all visuals, measures, and layout shown in the preview above — ready to open directly in Power BI Desktop. On open, Power BI will prompt you to point it at the source Excel file (`Excel Data Set/International Sales Performance Analysis (2021–2023).xlsx`) so it can load the data and refresh the visuals.

## Setup

1. Clone this repository (it's private, so make sure you're authenticated with GitHub):
   ```bash
   git clone https://github.com/ngcebo100/International-Sales-Performance-Analysis-2021-2023-.git
   ```
2. Open **Power BI Desktop** (download it [here](https://powerbi.microsoft.com/desktop/) if you don't have it).
3. Open `Excel Data Set/International_Sales_Performance_Analysis_2021-2023.pbit` from the cloned repo — Power BI will prompt you to select the data source; point it to `Excel Data Set/International Sales Performance Analysis (2021–2023).xlsx` in the same folder.
4. Power BI will load the data and render the dashboard automatically. From here you can explore the visuals as-is or customize them further.

## How to Use

- Open the workbook in Excel to explore or filter the raw data directly.
- Open the `.pbit` template in Power BI Desktop to load the pre-built dashboard and interact with it — filter by region, country, year, or item type to drill into specific segments.
- Use the visuals to compare revenue and profit trends across years and quarters, or identify top/bottom performing countries and product categories.

## Preview

See `Images/Shipment Report 2021 to 2023.png` in this repo for a full snapshot of the dashboard.
