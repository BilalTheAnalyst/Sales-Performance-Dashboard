📌 Sales Performance Dashboard – Project Story
🔹 Business Problem

The retail business was struggling to track sales, profit, and order performance across regions, product categories, and managers. Reports were mostly Excel-based, static, and time-consuming, making it difficult for decision-makers to:

Identify sales trends over time.

Track profitability per product, category, and region.

Monitor growth performance against last year.

Understand which stores, cities, and age groups were driving revenue.

🔹 Goal

To design an interactive, automated Sales Dashboard in Power BI that:

Provides real-time visibility into sales, profit, and orders.

Allows managers to drill down by Year, Category, Store, City, and Manager.

Tracks growth KPIs (MoM, YoY) to evaluate business performance.

Helps identify top-performing brands, stores, and regions for targeted strategies.

🔹 Tools Used

Power BI Desktop → For data modeling, DAX measures, and dashboard building.

Power Query → For data cleaning and transformations.

SQL (optional if used) → For preparing fact/dimension tables.

Excel / CSV files → As raw data sources.

🔹 Work Done

Data Preparation & Modeling

Loaded 4 years of sales data (Orders, Products, Customers, Stores).

Created a Star Schema with fact table (Sales) and dimension tables (Date, Product, Store, Manager, Region).

Built calculated columns and measures in DAX (Total Sales, Total Profit, Profit per Order, Sales Growth %, MoM Growth %).

Dashboard Design

Designed KPI Cards to show:

Total Sales vs Last Year

Total Profit vs Last Year

Total Orders vs Last Year

Profit per Order vs Last Year

Sales per Order vs Last Year

Used line charts to display monthly sales trends and growth %.

Added bar/column charts for:

Sales by SubCategory

Sales by StoreName

Sales by Brand

Added Donut Charts for:

Sales by Category

Sales by Region

Created Slicers for Year, Manager, and Age Group.

User Experience

Used consistent colors (green for growth, red for decline).

Designed an executive-friendly summary view at the top.

Enabled cross-filtering for deep dive analysis.

🔹 Insights & Results

From the dashboard, business leaders were able to see:

📈 Overall Sales Growth → $3.2M in sales with +321% growth YoY.

💰 Profitability → $2.3M profit with +220% growth.

🛒 Orders Trend → 4,000 orders, growing steadily MoM.

🏬 Top Regions → South and West contributed the majority of sales.

🎯 Top Categories → Home Office and Clothing performed best.

👥 Manager & Store Analysis → Store 7 and Store 5 were top contributors.

🔥 Brand Insights → Whirlpool, Nike, and Philips were top-performing brands.

⚡ City-Level Insights → Bangalore contributed the highest city sales.

🔹 Business Impact

✅ Automated reports → Reduced manual reporting effort.
✅ Faster decisions → Managers could track sales, profit, and growth in real time.
✅ Better strategy → Helped identify profitable products and underperforming stores.
✅ Improved visibility → Provided a single source of truth for sales performance.

ScreenShot
https://github.com/BilalTheAnalyst/Sales-Performance-Dashboard/blob/main/SalesReport.png
