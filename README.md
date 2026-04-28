# Superstore Sales & Performance Dashboard

An interactive 3-page Power BI dashboard analyzing 4 years of retail sales data 
to surface revenue trends, geographic distribution, customer loyalty, and 
profit-margin issues caused by aggressive discounting.

📁 Download the `.pbix` file above to open in Power BI Desktop, or scroll 
down for full screenshots of each page.

---

## Project Overview

Built using the Sample Superstore dataset (~10,000 retail transactions, 2023–2026). 
The dashboard answers four key business questions:

1. How is the business performing overall?
2. Which products and regions drive sales?
3. Why do some sub-categories lose money despite strong sales?
4. Who are our most valuable customers?

## Tools & Techniques

- **Power BI Desktop** — data modeling, multi-page report design, cross-page navigation
- **DAX time intelligence** — `SAMEPERIODLASTYEAR` for YoY comparison with a 
  dedicated marked Date table
- **Custom DAX measures** — Total Profit, Profit Margin, Average Order Value, 
  Repeat Purchase Rate, YoY Growth %, Sales per Customer
- **Interactive elements** — region/category slicers, page navigation buttons, 
  cross-filtering between visuals

## Dashboard Pages

### Page 1 — Sales Overview
Top-line KPIs (Total Sales, Profit, Margin, Orders, AOV, YoY Growth), US 
geographic distribution, profit by sub-category, and a year-over-year trend 
chart comparing current sales against the same period last year.

![Sales Overview](sales_overview.png)

### Page 2 — Product Performance
A discount-vs-profit scatter plot identifying the relationship between 
aggressive discounting and negative profit. Tables, Bookcases, and Supplies 
are flagged as loss-making sub-categories.

![Product Performance](product_performance.png)

### Page 3 — Customer Analysis
Customer segmentation, repeat-purchase rate, top 10 customers by sales, and 
geographic profit at the state level.

![Customer Analysis](customer_analysis.png)

## Key Insights

- **$2.33M total sales, $292K profit (12.5% margin)** with consistent 
  year-over-year growth and strong Q4 holiday seasonality.
- **3 sub-categories generate combined annual losses of ~$22,557** despite 
  strong sales volume. Root cause: average discount rates above 20% wipe 
  out margin.
- **Recommendation:** Cap discounts at 15% on Tables, Bookcases, and 
  Supplies. Based on the data, this could shift roughly $25–30K from 
  negative to positive annual profit.
- **98.5% repeat-customer rate** signals strong loyalty. Consumer segment 
  drives ~50% of total revenue.

## Files in This Repository

- `Superstore_Sales_Dashboard_Chitra_Varma.pbix` — Power BI source file
- `Sample_Superstore.csv` — raw dataset
- `sales_overview.png`, `product_performance.png`, `customer_analysis.png` — page screenshots

## How to Use

1. Download the `.pbix` file
2. Open with [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free)
3. Click through the three page tabs to explore each section
4. Use the slicers and filters to drill into regions, categories, and time periods

## About

Built by **Chitra Varma** — B.Sc Computer Science Graduate from Pillai 
HOC College, building a portfolio in data analytics and business intelligence.

🔗 LinkedIn: https://www.linkedin.com/in/chitra-varma-12aa28323/
📧 chitravarma.cyv@gmail.com
