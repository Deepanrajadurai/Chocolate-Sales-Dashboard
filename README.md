# 🍫 Chocolate Sales Dashboard
Interactive Power BI Dashboard for Chocolate Sales Analysis using DAX and Power Query.

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

Answers

Total Sales	$34M
Total Cost	$14M
Total Profit	$21M
Profit Margin	60%
Total Boxes	2M
Total Shipments	6K
```

## 🛠 Tools
Power BI • DAX • Power Query • Excel/CSV

## 📈 Key Insights
- Total Sales: $34M
- Profit: $21M
- Profit Margin: 60%
  📧 Contact

Contact
Deepan Rajadurai
📩 Email: rdeepan10112002@gmail.com
GitHub: https://github.com/Deepanrajadurai
- Regional comparison via donut chart
- Top products identified by sales and profit
