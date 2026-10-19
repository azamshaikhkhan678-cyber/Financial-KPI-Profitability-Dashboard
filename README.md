# Financial KPI Monitoring & Profitability Dashboard

## Project Objective
To build a corporate-ready Power BI dashboard that converts raw corporate financial records into dynamic, actionable analytics. This project tracks critical business health indicators including Total Revenue, Operational Costs, and Net Profit margins broken down by global sales regions and operational distribution channels.

## Analytics Infrastructure & Tools
* **Power BI Desktop:** Star schema design, interactive data filtering modeling, and asset layout.
* **Power Query Editor:** Strict column type checking, calendar attribute mapping, and structural row validation (null filtering).
* **Data Foundation Source:** Structured Comma-Separated Values (Notepad CSV file generation).

## Core Calculated Metrics (DAX Measures)
* `Total Revenue = SUM('financial_kpi_dataset'[Actual Revenue])`
* `Total Cost = SUM('financial_kpi_dataset'[Cost of Goods Sold]) + SUM('financial_kpi_dataset'[Operating Expenses])`
* `Total Net Profit = [Total Revenue] - [Total Cost]`

## Strategic Business Discoveries
* **Regional Value Concentration:** Surfaced immediate variations in financial metrics between diverse trading regions, highlighting high-performance market locations.
* **Channel Operational Efficiency:** Enabled comprehensive margin slicing through distinct inbound, partner network, and online portal business pathways to locate cost optimization openings.
