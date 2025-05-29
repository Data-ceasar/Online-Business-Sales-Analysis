# Online-Business-Sales-Analysis

This project presents a comprehensive data analysis of the sales performance of an online business using Google Sheets. It involves two datasets: one detailing product-level sales metrics and the other summarizing monthly sales performance. The entire analysis, visualization, and insight derivation are carried out using **only Google Sheets**, showcasing its capability as a lightweight but powerful tool for business intelligence.

---

## 🗂 Project Structure

**Sheet 1: Product-Level Sales Data**
- `Product Type`
- `Net Quantity`
- `Gross Sales`
- `Discounts`
- `Returns`
- `Total Net Sales`

**Sheet 2: Monthly Sales Summary**
- `Month`
- `Year`
- `Total Orders`
- `Gross Sales`
- `Discounts`
- `Returns`
- `Net Sales`
- `Shipping`
- `Total Sales`

---

## 📈 Key Analysis Performed

- **Data Cleaning & Validation:**  
I cleaned the raw data by first removing duplicates. 512 duplicates were found in Sheet1 and removed. No duplicates were found in Sheet2.
I ensured proper formatting, checked for missing values using `COUNTBLANK()`, and validated numerical consistency.

- **Time Series Preparation:**  
I combined the Month and Year columns into a single Date column using `=DATE(Year, Month, 1)` to enable timeline visualizations.

- **KPIs Calculated:**  
  - Return Rate
  - Discount Rate
  - Shipping Cost as % of Total Sales

- **Pivot Tables & Visualizations:**  
  - Sales by Product Type
  - Time-based trends in Net Sales and Orders

---

## 📊 Visualizations

All charts and visuals are generated using Google Sheets:
- Bar charts for top-performing product types.
- Line charts for monthly sales trends.
- Pie charts for sales distribution by category.
- Scatter Plot for correlation analysis between the number of orders and Net sales.

---

## ✅ Insights Derived

The highest-performing product type was the Basket, accounting for 36% of net sales. The top 5 highest performing products are Basket, Art & Sculpture, Jewelry, Home Decor, and Christmas.
- The number of orders in the 4th quarter is consistently higher than that of other quarters. This may be due to the holiday season. However, the number of orders in the 4th quarter of 2019 was significantly higher than in previous years. This was due to pre-purchase in response to the COVID-19 pandemic.
- There was a spike in shipping costs in the 4th quarter of 2019 compared to other periods. This is due to the rise in demand for online purchases in the same period.

---

## 📁 How to Use

1. Open the Google Sheets file via the provided link.
2. Navigate between the sheets using the tabs at the bottom.
3. Explore the **dashboard section** for visual insights.
4. Use the slicers to interact with the data dynamically.

---

## 📌 Tools Used

- Google Sheets (formulas, charts, pivot tables, conditional formatting)
- Basic spreadsheet functions (e.g., `SUMIF`, `IF`, `COUNTBLANK`, `QUERY`, `DATE`, `VLOOKUP`)

---

## 🧠 Motivation

This project demonstrates that meaningful data analysis and decision-making can be achieved without advanced BI tools, just with structured thinking and Google Sheets. It's ideal for small businesses, students, or anyone learning data analytics on a budget.

