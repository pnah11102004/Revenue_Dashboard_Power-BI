# 📊 Beyou Sales Dashboard — Power BI
An interactive Power BI dashboard designed to analyze sales performance, profitability, and regional dynamics at Beyou, a global cycling equipment company. The report helps business leaders and sales managers gain a clear view of revenue trends, geographic opportunities, and individual salesperson effectiveness — all within a single, filterable interface.

## 📁 Project Structure
📦 powerbi-lab10

 ┗ 📊 powerbi_lab10.pbix      # Power BI Desktop report file

## 📸 Dashboard Preview
### 🏠 Home

<img width="1266" height="705" alt="image" src="https://github.com/user-attachments/assets/ec028002-610d-45bf-a916-4240bf631873" />

### 📈 Overview

<img width="1261" height="703" alt="image" src="https://github.com/user-attachments/assets/3b15ba4d-9fbd-4c1c-8220-f10b5588c6a2" />

### 🗺️ Region Analysis

<img width="1267" height="700" alt="image" src="https://github.com/user-attachments/assets/412f7a40-3808-43ad-9e56-627bda64f91e" />

### 💼 Sale Analysis

<img width="1262" height="698" alt="image" src="https://github.com/user-attachments/assets/b5a2126e-738d-4719-b4b8-991703df7e5e" />

## 📊 Key Features

- KPI snapshot of Total Sales, Total Cost, Avg Unit Price, Profit, and Profit Margin
- Year-over-Year (YoY) sales growth rate tracked across countries
- Tornado chart comparing monthly Sales vs. Cost across the fiscal calendar
- Geographic bubble map visualizing profit and sales concentration by country
- Breakdown of sales and orders by individual salesperson and top resellers
- Top-N filtered ranking of highest-profit products
- Interactive filtering across 5 dimensions: Date, Region Group, Country, Sales Type, and Salesperson


## 🧹 Data Preparation
The report was built on a structured sales dataset spanning multiple business dimensions. Key preparation steps included:

- Modeling relationships across 6 tables: Sales, Date, Product, Region, Salesperson, and Reseller
- Building a Fiscal Calendar hierarchy (Month → Quarter → Year) for time-intelligence analysis
- Engineering DAX measures for Profit, Profit Margin, Orders count, and YoY Growth %
- Applying Top-N visual-level filters on Reseller and Product charts to surface high-impact entries
- Embedding a Max Date measure on the Home page to surface data freshness at a glance


## 📁 Tools & Technologies

- Power BI Desktop: DAX measures, custom Tornado Chart visual, cross-page slicer sync, page navigation buttons
- Power Query: Data shaping and table relationship modeling
- Beyou Dataset: Simulated enterprise sales database across regions, products, and personnel
- Dark-mode UI: Professional dark theme for improved readability and visual contrast


## 🧠 Data Insights
The dashboard enables users to:

- Monitor overall business health through five core financial KPIs at a glance
- Identify which countries and regions generate the highest profit margins
- Compare Sales vs. Cost month-by-month to detect seasonal pressure on margins
- Pinpoint top-performing and underperforming salespersons by revenue and order volume
- Discover which resellers and products drive the most profit, enabling data-driven prioritization
- Explore correlations between product category mix and profitability across geographies


## 🚀 Getting Started

Clone or download this repository

Open powerbi_lab10.pbix with Power BI Desktop (free)
Use the navigation buttons on the Home page to jump to each analysis section
Apply slicers on any page to filter by Date, Region, Country, Sales Type, or Salesperson — filters are synchronized across all pages


Requirement: Power BI Desktop — August 2024 or later recommended. No external data connection needed; all data is embedded in the .pbix file.


## 📜 License
This project is for educational purposes, based on the Beyou sample dataset.
