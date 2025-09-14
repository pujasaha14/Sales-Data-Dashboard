📊 Project Summary – Sales Data Dashboard

🎯 Objective

The goal of this project was to design and implement a Sales Data Dashboard to help business decision-makers track revenue, profitability, customer behavior, and sales performance. The dashboard consolidates raw sales data, lead pipeline data, and time intelligence into interactive KPIs and visualizations, enabling insights into business growth, regional trends, customer retention, and forecasting.

📂 Data Sources

Sales Dataset (sales_dataset_large.csv)

Contains transaction-level details: Date, Product, Region, Sales, Cost, Discount, CustomerID.

Date Table (date_table.csv)

Full-year calendar table (2023–2025) with Year, Quarter, Month, Week, Day, Weekend flag.

Lead Table (lead_table.csv)

Simulated sales pipeline data with LeadID, LeadDate, Region, Channel, LeadStatus, Opportunity Value, CloseDate, and IsConverted.

📈 Key KPIs Designed

Revenue Metrics: Total Sales Revenue, Revenue Growth %, Average Order Value (AOV).

Profitability Metrics: Gross Profit, Profit Margin %, Net Profit.

Customer Metrics: Retention Rate, Churn Rate, Customer Acquisition, Customer Lifetime Value (CLV).

Sales Performance Metrics: Top Products, Sales by Region, Sales by Channel, Conversion Rate.

Operational Metrics: Pipeline Value, Average Sales Cycle Length, Discount Impact.

Trend & Forecast Metrics: Monthly/Quarterly Sales Trends, Forecasted Sales, Seasonality Analysis.

📊 Dashboard Design in Power BI

Top Row (KPI Cards): Large summary cards showing Revenue, Profit Margin, AOV, Retention, Growth %.

Trends & Regional Performance: Line chart of sales & profit over time, map/bar chart for regional sales.

Products & Channels: Top 10 products (Pareto analysis), donut chart for channel performance.

Customer Journey: Funnel chart for Leads → Opportunities → Deals, gauge for Retention Rate.

Profitability Analysis: Scatter plot of Discounts vs Profit Margin.

Advanced Section: Forecasted sales (time series) and heatmap for seasonal sales trends.

🛠 Tools & Techniques

Power BI: Data modeling, DAX measures, dashboard design.

DAX Calculations: For KPIs (Revenue, Profit, Retention, Growth %, etc.).

Python & Pandas: Data preprocessing, synthetic data generation (Lead Table, Date Table).

Visualization Techniques: KPI cards, line charts, bar charts, maps, pie/donut charts, funnel, gauge, scatter, heatmaps.

🚀 Impact

The dashboard enables business leaders to:

Monitor financial health (Revenue, Profit, Margins).

Track regional and product-level performance.

Improve customer retention and acquisition strategies.

Evaluate effectiveness of sales channels and discounts.

Forecast future sales and identify seasonal trends.

