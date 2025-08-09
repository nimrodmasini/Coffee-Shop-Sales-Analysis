# ☕ Coffee Shop Sales Analysis
An interactive dashboard analyzing sales trends, product performance, and store location insights for a fictional coffee shop.

![Coffee Shop Dashboard](https://github.com/user-attachments/assets/f6cdd73a-9a79-474a-a2cd-4d597e800e78)

---

## Project Description
**Project Purpose:**
The Coffee Shop Sales Analysis Dashboard was created to help store managers and business owners monitor sales performance, customer preferences, and seasonal trends. By analyzing daily transaction data, the dashboard provides actionable insights to identify peak sales periods, understand product category performance, optimize staffing and inventory decisions and improve profitability through targeted promotions.

**Technologies Used:**
- Excel
- Pivot Tables
- Excel Visualizations

---

## Data and Processing

**Data Source:**
The dataset was sourced from Maven Analytics – Coffee Shop Sales. It contains point-of-sale transaction data from a fictional coffee shop chain, including Transaction details, Product details and Sales metrics. The data covers a 6-month period and is designed to simulate real-world coffee shop sales patterns.

**Data Cleaning:**
- Checked for and removed repeated transaction IDs.
- Unified date and time formats, standardized product naming conventions.
- Checked unit prices and quantities for valid ranges.
- Extracted Year, Month, Day, and Hour for time-based analysis.

**Data Modeling:**
- **Pivot Tables** - Built multiple pivot tables to summarize sales by date, product, and location.
- **Date Hierarchy** - Extracted Year, Month, Day, and Hour from transaction timestamps using Excel date functions.
- **Calculated Columns & Measures**  Used Excel formulas to create derived metrics.

**Metrics Created:**

```excel
Revenue = unit_price * transaction_qty
Total Transactions = COUNTA(UNIQUE(transaction_id))
Total Quantity Sold = SUM(transaction_qty)
Average Transaction Value = SUM(Revenue) / [Total Transactions]
```

--- 

## Key Insights
- **Revenue Trend** - Sales rose steadily from January (~$26K) to May (~$51K) before slowing slightly in June.
- **Top Days** - Monday records the highest transactions. Sunday has the lowest.
- **Peak Hours** - 8 AM to 10 AM see the highest activity, showing strong morning demand.
- **Product Category Leaders** - Coffee and Tea dominate transactions, with Bakery items ranking third.
- **Top Products** - Barista Espresso and Gourmet Brewed Coffee lead in both transactions and revenue.

---

## Recommendations
- Offer breakfast combo deals during peak 8–11 AM to increase basket size.
- Run discounts or loyalty rewards on Sundays to drive more traffic.
- Promote Gourmet Brewed Coffee and Barista Espresso with in-store ads.
- Bundle bakery products with coffee during morning rush hours.
