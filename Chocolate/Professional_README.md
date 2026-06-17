# 🍫 Chocolate Sales Dashboard

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?logo=powerbi)
![DAX](https://img.shields.io/badge/DAX-Measures-blue)
![Power Query](https://img.shields.io/badge/Power%20Query-ETL-green)
![SQL](https://img.shields.io/badge/SQL-Analytics-orange)
![License](https://img.shields.io/badge/License-MIT-brightgreen)

## 📌 Overview
An interactive Power BI dashboard for analyzing chocolate sales, profitability, shipments, product performance, and regional trends.

## 🎯 Business Problem
Chocolate manufacturers generate millions of sales transactions across multiple countries and product categories. Business leaders need a single dashboard to:
- Track KPIs (Sales, Cost, Profit, Profit %)
- Monitor monthly performance
- Compare regional sales
- Identify high-performing products
- Analyze shipment distribution
- Support data-driven decisions

## 📊 Dashboard Features
- KPI Cards
- Monthly Trend Analysis
- Product-wise Profitability
- Region-wise Sales Distribution
- Country & Product Slicers
- Custom Tooltip Page

## 🧮 DAX Measures
```DAX
Total Sales = SUM(Sales[Sales])
Total Cost = SUM(Sales[Cost])
Profit = [Total Sales]-[Total Cost]
Profit % = DIVIDE([Profit],[Total Sales],0)
Total Boxes = SUM(Sales[Boxes])
```

## 🛠 Tools
Power BI • DAX • Power Query • Excel/CSV

## 📈 Key Insights
- Total Sales: $34M
- Profit: $21M
- Profit Margin: 60%
- Regional comparison via donut chart
- Top products identified by sales and profit
