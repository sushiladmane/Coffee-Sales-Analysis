## 📌 Project Overview
This project presents an interactive **Coffee Sales Dashboard** built using **Power BI**.  
The dashboard helps analyze sales performance, customer payment behavior, and best-selling coffee products.

---

## 🎯 Objectives
- Analyze total sales and order trends
- Identify best-selling coffee types
- Compare card vs cash payments
- Track monthly sales performance
- Provide business-ready insights through visuals

---

## 📊 Dashboard Features
- KPI Cards: Total Sales, Total Orders, Card Sales, Cash Sales
- Monthly Sales Trend (Line Chart)
- Sales by Coffee Type (Bar Chart)
- Units Sold by Coffee Type
- Payment Type Distribution (Donut Chart)
- Interactive Slicers (Date, Payment Type, Coffee Type)
- Domain-specific coffee theme design

---

## 🧾 Dataset Columns
- `date`
- `datetime`
- `cash_type`
- `card_money`
- `coffee_type`

## 🧮 DAX Measures Used

```DAX
Total Sales = SUM(Sales[cash_type]) + SUM(Sales[card_money])

Total Orders = COUNTROWS(Sales)

Cash Sales = SUM(Sales[cash_type])

Card Sales = SUM(Sales[card_money])# Coffee-Sales-Analysis

