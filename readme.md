# 🛍 Superstore Sales Dashboard in Excel

This Excel project presents a comprehensive *Sales Analysis Dashboard* built using *Superstore data*. It includes thorough data cleaning, feature engineering, visual analytics using PivotTables and charts, interactive slicers, and KPI tracking to derive key business insights.

---

## 📌 Features

- ✅ Cleaned and pre-processed raw Superstore data
- 🧮 Created new columns:
  - *Order Month* and *Quarter* (for trend analysis)
  - *Discount Group* (to categorize profits by discount range)
  - *Average Profit Margin*
  - *Days to Ship* (difference between order date and ship date)
- 📊 Built 4 PivotTables for dynamic data exploration:
  1. *PT_SalesTrends*: Sales, Profit, and Profit Margin over time (by Year and Month)
  2. *PT_ProductAnalysis*: Metrics by Category and Sub-category (Furniture, Office Supplies, Technology)
  3. *PT_GeoAnalysis*: Region-wise and State-wise sales insights (East, West, Central, South — USA only)
  4. *Top 5 Products*: Highest selling products based on total sales
- 📌 Created a *KPI_Helper* sheet with:
  - Total Orders
  - Total Customers
- 📈 Designed an interactive *Dashboard*:
  - *Line Chart* for sales trends (from PT_SalesTrends)
  - *Bar Chart* for product performance (from PT_ProductAnalysis)
  - *Column Chart* for regional analysis (from PT_GeoAnalysis)
  - *Pie Chart* for Top 5 products by sales
- 🧩 Added *Slicers* for:
  - Month
  - Quarter
  - Category
  - Subcategory
  - States
  - City
- 🃏 Flashcards for KPIs:
  - Total Sales
  - Total Profit
  - Total Orders
  - Total Customers
  - Avg. Profit Margin
- 🖱 *Macro* to reset all slicer filters with a single click

---

## 🚀 How to Use

1. *Download or clone* the repository.
2. Open Superstore_Dashboard.xlsm in Excel.
3. Enable content/macros when prompted.
4. Use *slicers* to filter data interactively.
5. Click the *Reset Filters* button to clear all slicer selections.

---

## 📊 Insights Extracted

- Peak months and quarters for sales and profits
- Most and least profitable discount ranges
- Best and worst performing product categories and subcategories
- Region-wise and state-wise business performance
- Top 5 high-selling products in the market

---

## 🛠 Tools & Techniques

- Microsoft Excel
- PivotTables & PivotCharts
- Slicers
- Flashcards (Dynamic KPIs)
- VBA Macros (for reset functionality)
- Data Cleaning and Feature Engineering

---

## 🧠 What I Learned

- Real-world data cleaning and preprocessing
- Advanced Excel functions: TEXT, DATEDIF, IF, etc.
- Designing dynamic dashboards
- Enhancing interactivity with slicers and macros
- Business insight derivation from visual data