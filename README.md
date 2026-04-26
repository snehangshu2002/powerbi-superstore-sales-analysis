# Superstore Sales Dashboard

An interactive Power BI dashboard analyzing four years of retail sales data (2014 to 2017) across categories, regions, and time periods for a fictional US-based superstore.

---

## Dashboard Preview

![Demo Image](https://raw.githubusercontent.com/snehangshu2002/powerbi-superstore-sales-analysis/main/demo.png)
---

## Project Summary

This dashboard was built to answer a few practical questions: which categories are actually profitable, where are losses concentrated, and how has revenue moved over time. The result is a single-page report with slicers, a geographic view, and a profit breakdown that makes regional performance easy to compare at a glance.

---

## Key Metrics (All Years)

| Metric | Value |
|---|---|
| Total Revenue | $1.83M |
| Net Profit | $224.78K |
| Profit Margin | 12% |
| Total Orders | 3,971 |
| Average Order Value | $460 |

---

## Visuals Included

**Revenue Trend Over Time** tracks total sales from 2014 to 2017. Revenue grew steadily from $0.48M to $0.73M, with the steepest jump between 2016 and 2017.

**Revenue Contribution by Category** is a donut chart showing the split across Technology ($673.37K), Furniture ($581.81K), and Office Supplies ($571.48K). Technology leads by a small margin but all three are competitive.

**Revenue by Region** is a bar chart ranking West ($585.49K), East ($522.45K), Central ($398.37K), and South ($320.36K). West and East together account for more than 60% of total revenue.

**Top 5 Sub-Categories by Revenue** shows Phones at the top, followed by Chairs, Storage, Tables, and Binders.

**Geographic Distribution** is a Bing Maps bubble map showing order concentration across US states.

**Key Drivers of Profit** is a treemap breaking down profit by region. West leads with $87.93K, followed by East ($70.43K), South ($38.43K), and Central ($27.99K).

---

## Filters

The dashboard includes a year slicer that lets you filter across 2014, 2015, 2016, and 2017, individually or in any combination. All visuals update together. There are also toggle buttons to switch the main KPI view between Revenue and Profit.

---

## Data

- Source: Superstore Sales dataset (commonly used for BI training and portfolio projects)
- Time range: January 2014 to December 2017
- Scope: US sales data across three product categories and four regions

---

## Tools Used

- Power BI Desktop for report building and DAX measures
- Microsoft Bing Maps for geographic visualization
- DAX for calculated columns and KPI measures

---

## How to Use

1. Open the `.pbix` file in Power BI Desktop.
2. Use the year slicer (top right) to filter by one or more years.
3. Click any bar, slice, or region on the map to cross-filter the other visuals.
4. Toggle between Revenue and Profit views using the buttons on the top right.

---

## Findings Worth Noting

Phones are the top sub-category by revenue and also the most profitable single item ($261.6K shown in the highlight card). Central region consistently underperforms despite being the third-largest by revenue, which suggests a discount or cost problem worth investigating. South has the lowest revenue and profit, but its profit margin is not drastically worse than Central's, so the gap is mostly a volume issue.

---

## Author

**Snehangshu Bhuin**  
Data Analyst | M.Sc. Statistics, Visva-Bharati University  
[GitHub](https://github.com/snehangshu2002) | [LinkedIn](https://www.linkedin.com/in/snehangshu-bhuin)
