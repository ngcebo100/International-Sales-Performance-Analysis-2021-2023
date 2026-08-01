# Global Sales & Revenue Dashboard (2021–2023) 📊

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Excel-217346?style=flat&logo=microsoftexcel&logoColor=white)
![Status](https://img.shields.io/badge/status-active-success)

An interactive Power BI dashboard analyzing global sales and revenue data from 2021 to 2023, built from a dataset of ~1,700 order records spanning multiple regions, countries, and product categories.

![Dashboard Preview](Shipment_Report_2021_to_2023.png)

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

The dataset (`Shipment_Report_2021_to_2023.xlsx`) contains order-level records with the following fields:

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

## Setup

1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/<your-repo-name>.git
   ```
2. Open **Power BI Desktop** (download it [here](https://powerbi.microsoft.com/desktop/) if you don't have it).
3. In Power BI, go to **Get Data → Excel** and select `Shipment_Report_2021_to_2023.xlsx` from the cloned repo.
4. Build or recreate the visuals using the fields described in the [Data](#data) section above, or reference the preview image for layout guidance.

## How to Use

- Open the workbook in Excel to explore or filter the raw data directly.
- Load the data into Power BI Desktop to interact with the dashboard — filter by region, country, year, or item type to drill into specific segments.
- Use the visuals to compare revenue and profit trends across years and quarters, or identify top/bottom performing countries and product categories.

## Preview

See `Shipment_Report_2021_to_2023.png` in this repo for a full snapshot of the dashboard.
