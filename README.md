📊 Vendor Performance Analysis

An end-to-end data analytics pipeline to evaluate vendor sales performance, detect trends, and generate actionable business insights using Python, SQL, SQLite, and Power BI.


🔍 Problem Statement
Companies often face financial losses due to:

Poor inventory management and slow-moving stock
Inefficient pricing strategies
Over-dependence on a few vendors

This project answers key business questions:

Which vendors contribute the most to sales and gross profit?
Which brands are underperforming and need pricing/promotional adjustments?
How does bulk purchasing affect unit cost?
What is the inventory turnover rate per vendor?
What is the profitability variance between high and low-performing vendors?


🎯 Objectives

Identify top-performing vendors by sales and gross profit contribution
Detect underperforming brands requiring marketing or pricing adjustments
Analyze the impact of bulk purchasing on unit costs
Assess inventory turnover to reduce holding costs
Deliver a business report with actionable recommendations


🗂️ Project Structure
Vendor-Performance-Analysis/
│
├── data/
│   └── vendor_sales_summary.csv       # Cleaned aggregated dataset
│
├── notebooks/
│   ├── Exploratory Data Analysis.ipynb        # EDA with visualizations
│   └── Vendor Performance Analysis.ipynb      # Full analysis notebook
│
├── scripts/
│   ├── ingestion_db.py                # Loads raw data into SQLite DB
│   └── get_vendor_summary.py          # Auto-generates vendor summary report
│
├── dashboard/
│   └── vendor_performance.pbix        # Power BI dashboard file
│
├── reports/
│   └── Vendor Performance Report.pdf  # Final business insights report
│
└── README.md

🛠️ Tech Stack
ToolPurposePython 3.xCore programming languagePandasData cleaning and manipulationMatplotlib / SeabornEDA visualizationsSQLiteLightweight local databaseSQLQuerying and aggregating dataJupyter NotebookInteractive analysis environmentPower BIInteractive KPI dashboard





📈 Key Insights

Top 5 vendors contributed over 80% of total gross profit
Vendors with high bulk purchase volume showed significantly lower unit costs
Several brands had high stock levels but low sales — indicating poor inventory turnover
A clear profitability gap was observed between top and bottom-tier vendors
Some vendors showed strong purchase frequency but below-average profit margins


📊 Power BI Dashboard — KPIs Tracked

Total Sales & Gross Profit by Vendor
Sales Contribution % per Vendor
Inventory Turnover Rate
Purchase Order Frequency
Profit Margin Comparison (Top vs Low Performers)
Bulk Purchase vs Unit Cost Trend


💡 Business Recommendations

Diversify vendor base — reduce dependency on top 2–3 suppliers to mitigate supply chain risk
Leverage bulk purchasing — negotiate better rates with high-volume vendors
Clear slow-moving inventory — launch clearance pricing or reduce reorder quantities for low-turnover stock
Adjust pricing strategy — revisit margins for vendors with high sales but low profit
Support underperforming brands — targeted promotions and marketing to increase their contribution


📋 Resume Highlights

Built an end-to-end data analytics pipeline using Python & Pandas to ingest, clean, and analyze vendor sales data stored in SQLite
Performed Exploratory Data Analysis (EDA) to identify top-performing vendors, profit margins, and inventory turnover trends from 10,000+ records
Developed an automated vendor summary report generation script reducing manual reporting effort and enabling repeatable analysis
Designed an interactive Power BI dashboard with KPIs including gross profit, purchase contribution, and stock health for business decision-making
Delivered a comprehensive business insights report with actionable recommendations on bulk pricing strategy, vendor diversification, and inventory optimization


