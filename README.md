# H1 2023 Coffee Shop Business Performance Review

## Project Overview
This project analyzes the H1 2023 business performance of a coffee shop chain using SQL and Tableau.  
The analysis focuses on three business dimensions:

- **Overall revenue trend** across the first half of 2023
- **Coffee product performance**, including top revenue-driving products and revenue vs. sales volume comparison
- **Store-level performance**, comparing revenue and sales volume across store locations

The project was designed to simulate a business performance review scenario and identify opportunities for pricing, product mix, and store-level revenue optimization.

---

## Business Questions
This project aims to answer the following questions:

1. **How did the coffee shop’s overall business performance change across H1 2023?**  
   Focus: monthly revenue trend, growth pattern, and whether there were early signs of slowing momentum.

2. **Which coffee products were the main revenue drivers, and how did revenue compare with sales volume across top products?**  
   Focus: top-performing products by revenue, concentration of revenue contribution, and potential differences between volume and revenue performance.

3. **Why did store revenue performance differ across locations despite similar sales volume?**  
   Focus: comparison of revenue vs. sales volume across stores and identification of store-level pricing or product-mix differences.

---

## Key Findings
- **Revenue growth remained positive overall**, with revenue increasing from **$81.7K in January** to **$166.5K in June**, although the pace of growth appeared to moderate toward the end of the period.
- **Revenue performance was shaped by both volume and product mix.** Some coffee products delivered strong revenue contribution, while others achieved relatively high sales volume without proportionate revenue contribution.
- **Store revenue differences were not driven by volume alone.** Lower Manhattan recorded the highest sales volume among the three stores, but Hell’s Kitchen generated the highest revenue, suggesting differences in pricing, product mix, or average selling price across locations.

---

## Dashboard Preview
The Tableau dashboard summarizes:
- monthly revenue trend
- top coffee product performance
- store-level revenue vs. sales volume comparison
<img width="1413" height="805" alt="dashboard_overview" src="https://github.com/user-attachments/assets/3ba9f1e6-6051-40a5-b2f3-1ef646fbb520" />

> Tableau Public dashboard link:**(https://public.tableau.com/views/H12023CoffeeShopBusinessPerformanceDashboard/H12023CoffeeShopBusinessPerformanceDashboard?:language=zh-CN&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)]**  
> Notion project page: **https://app.notion.com/p/H1-2023-Coffee-Shop-Business-Performance-Review-392279450f9f8051aa69d4d80895eee1?source=copy_link**

--

## Project Structure
```text
coffee-shop-business-performance-review
├── sql
│   ├── 01_monthly_revenue_trend.sql
│   ├── 02_coffee_product_performance.sql
│   ├── 03_store_monthly_performance.sql
│   └── 04_store_revenue_vs_sales_volume.sql
│
├── exports_for_dashboard
│   ├── 01_monthly_revenue_trend.csv
│   ├── 02_coffee_product_performance.csv
│   ├── 03_store_monthly_performance.csv
│   └── 04_store_revenue_vs_sales_volume.csv
│
├── dashboard_assets
│   ├── coffee_shop_h1_2023_dashboard.twb
│   └── dashboard_overview.png
│
├── final_screenshots
│   ├── notion_project_overview.png
│   ├── dashboard_embedded_in_notion.png
│   └── business_recommendations.png
│
└── notion_materials
    ├── project_writeup.md
    └── tableau_public_link.txt
```

---

## Tools Used
- **SQL** — data extraction and business analysis
- **Tableau Public** — dashboard design and visualization
- **Notion** — project presentation and narrative write-up
- **GitHub** — project documentation and repository management

---

## Business Recommendations
Based on the analysis, the following actions were recommended:

1. **Monitor revenue momentum after June more closely.**  
   Revenue continued to grow, but the growth rate appeared to moderate relative to earlier months.

2. **Review high-volume but lower-revenue products for pricing and product-mix opportunities.**  
   Strong sales volume did not always translate into equally strong revenue performance.

3. **Further evaluate Lower Manhattan’s product mix and pricing structure.**  
   Lower Manhattan outperformed Hell’s Kitchen in sales volume during some periods but still lagged in revenue, suggesting weaker revenue conversion at the store level.

---

## Notes
This project was built as part of a portfolio focused on business/data analyst roles.  
It demonstrates the ability to:
- translate business questions into SQL analysis
- prepare structured outputs for dashboarding
- interpret results from both product and store performance perspectives
- communicate findings through dashboard storytelling and written business recommendations
