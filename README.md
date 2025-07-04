# DataAnalysis-Power-BI

# 🌍 Sales Analysis Dashboard using Power BI

This project showcases an end-to-end data analysis using Power BI — from data cleaning to visualization — designed to help stakeholders like CEOs and CMOs gain actionable insights from global sales data.

---

## 📁 Dataset Overview

The dataset includes sales transaction details with fields such as:
- `Invoice Date`
- `Country`
- `Customer ID`
- `Product`
- `Quantity`
- `Unit Price`

---

## 🧹 Data Cleaning Performed

- Removed records with `Quantity < 1` to eliminate invalid entries.
- Excluded rows with missing or blank `Customer ID`.
- Created a new calculated column:  
  📌 **Revenue = Quantity × Unit Price**
- Filtered dataset to include only data for the year **2011**.
- Created a formatted column `YearMonth` (e.g., `2011-03`) for monthly granularity.

---

## 📊 Visualizations

### 1. **Line Chart - Monthly Revenue Trend (2011)**
- **X-axis:** YearMonth
- **Y-axis:** Total Revenue
- Shows how revenue changed each month across 2011.

### 2. **Column Chart - Top 10 Customers by Revenue**
- Displays the highest contributing customers.
- Filtered to exclude blank Customer IDs.
- Shows revenue per customer.

### 3. **Map Chart - Global Units Sold by Country**
- Highlights each country with total units sold.
- Interactive bubbles show country name and units on hover.
- Gives the CEO a global view of sales distribution.

### 4. **Clustered Bar Chart - Revenue by Product (Side-by-Side)**
- Visual comparison of revenue across different products and months.

---

## 🧠 Key Insights

- Identified the **top-performing customers** contributing most revenue.
- Visualized the **monthly revenue trend** to spot seasonal patterns.
- Used maps to reveal **high-volume countries** in terms of units sold.
- Ensured **data quality** by excluding invalid or incomplete records.

---

## 📌 Tools Used

- Power BI Desktop
- DAX (for calculated columns and measures)
- Power Query (for filtering and shaping data)

---

## 💼 Business Impact

This analysis helps executives:
- Monitor monthly sales performance.
- Identify and reward high-value customers.
- Target countries with strong or weak sales volumes.
- Make informed decisions based on clean, visualized data.



