### Pizza Sales Analysis Dashboard
```markdown
## Overview 
This project builds a comprehensive Pizza Sales Dashboard using SQL for data preparation and Power BI for visualization.
The dashboard provides business users with actionable insights into sales performance, product preferences, and operational trends.
```
```markdown
## 📊 Power BI Dashboard

The project also includes a fully interactive Power BI dashboard to visually explore churn patterns and insights.

📁 File: `Dashboard/PizzaSalesDashboard.pbix`  
🖼️ Preview: Home tab

![Power Bi Dashboard](screenshots/dashboard_main.png)

🖼️ Preview: Best/Worst Sellers tab

![Power Bi Dashboard](screenshots/best_worst_sellers.png)
```
```markdown
## Features

- Dynamic KPI Cards: Total Revenue, Avg Order Value, Total Pizzas Sold, Total Orders, Avg Pizzas Per Order
- Time-based Trends: Daily and Monthly Order Volumes
- Sales Breakdown: By Pizza Category and Size
- Top 5 and Bottom 5 Products: Revenue, Quantity, Orders
- Fully Interactive Slicers and Filters for dynamic analysis

## Project Structure

pizza-sales-dashboard/
├── dashboard/
│ └── PizzaSalesDashboard.pbix
├── assets/
│ └── bar graph.png
│ └── delivery-man.png
│ └── down-arrow.png
│ └── order-delivery.png
│ └── pizza-slice.png
│ └── profit-growth.png
│ └── test.png
├── data/
│ └── pizzasalesdata.csv
├── screenshots/
│ └── dashboard_main.png
│ └── best_worst_sellers.png
├── README.md
├── executive summary.docx
├── pizza sales sql queries.docx
├── problem_statement.docx

## Process & Tools Used

- **MS SQL Server:** Data import and business logic computation via SQL queries.
- **Power BI (June 2025 ver.):** Data modeling, cleaning, and interactive dashboard/report creation.
- **CSV Sales Data:** Raw transactional data used for analytics.
```
```markdown
## Project Steps

1. Import pizza sales data into SQL Server; ensure column data types and integrity.
2. Write SQL queries for KPIs, order trends, and product breakouts as defined by the problem statement.
3. Validate SQL results, export for use in Power BI or connect directly for live data.
4. Clean/process data in Power BI as required (Power Query, calculated columns/measures).
5. Design dashboards per requirements: KPIs, trends, distributions, and product analysis.
6. Implement drill-through, dynamic filtering, and navigation for maximum usability.

## Insights Gained

- Peak sales occur on weekends, especially Fridays.
- Large pizzas and Classic/Supreme categories are most ordered.
- Seasonal dips detected in September; consider targeted promotions.
- Best sellers identified for potential upselling; underperformers for menu optimization.
```
```markdown
## Getting Started

1. Clone this repo.
2. Connect to your local or cloud SQL Server with the provided schema and data.
3. Open the Power BI file and refresh data source or connect to your own.
4. Explore the dashboard and gain insights.
```
