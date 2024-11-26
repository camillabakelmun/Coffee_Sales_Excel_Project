# Coffee_Sales_Excel_Project
An interactive Excel dashboard analyzing coffee sales data for a fictional online shop, Daily Grind Coffee Co. Includes a professional report summarizing key findings and recommendations. This project highlights data cleaning, pivot tables, advanced Excel skills, and actionable business insights.
# **Coffee Sales Dashboard Project ☕**

## **Overview**
This project demonstrates an advanced Excel-based analysis of sales data for *Daily Grind Coffee Co.*, a fictional small business specializing in selling coffee beans online. As a data analyst, my objective was to analyze sales trends, identify top customers and products, and provide actionable insights to help the business optimize marketing efforts and increase sales.

The project showcases data cleaning, advanced Excel functions, pivot tables, interactive dashboards, and professional formatting.

---

## **Objective**
To analyze sales data for *Daily Grind Coffee Co.* from 2019–2022 and deliver actionable insights through a professional Excel dashboard.

### **Key Questions**
1. **When are the best and worst-performing months for sales?**
2. **Which country generates the most revenue?**
3. **Who are the top customers, and how can customer retention improve?**
4. **Which coffee beans are the most popular?**

---

## **Steps Taken**

### **Data Cleaning**
1. **Merged Data:**
   - Combined customer data with orders using the `XLOOKUP` function.
   - Imported product details using the `INDEX` function.
2. **Cleaned Columns:**
   - Replaced abbreviations in “Coffee Type” and “Roast Type” with full names using the `IF` function (e.g., "Ara" → "Arabica").
3. **Formatted Data:**
   - **Dates:** Used a custom format (e.g., 05-Sep-2019) for clarity.
   - **Size:** Limited to one decimal place and displayed in kilograms (kg).
   - **Currency:** Applied currency formatting to unit price and sales columns.
4. **Checked for Duplicates:** Confirmed none existed.
5. **Converted to Table:** Formatted the dataset as a table for easier analysis.

### **Analysis**
1. Created Pivot Tables for:
   - Total Sales by Date, Coffee Type, and Sales (visualized as a 2D line chart).
   - Total Sales by Country (bar chart).
   - Top 5 Customers by Sales (bar chart).
2. Added Slicers and Timelines:
   - Enabled dynamic filtering by roast type, size, and loyalty card status.
3. Calculated Best and Worst Performing Months:
   - **Best Month:** February 2020 ($1,798.34).
   - **Worst Month:** August 2022 ($244.25).
4. Identified Key Metrics:
   - **Total Sales:** $45,134.26.
   - **Top-Selling Coffee Bean:** Excelsa ($6,112 in total sales).
   - **Top Revenue-Generating Country:** United States ($35,639).

### **Dashboard Creation**
1. Integrated all charts into a cohesive, interactive dashboard.
2. Applied a professional theme inspired by earthy coffee tones.
3. Ensured slicers and timelines updated all charts seamlessly.
4. Aligned and formatted elements for a polished, user-friendly experience.

---

## **Key Insights**
1. **Best Month:** February 2020 saw the highest sales ($1,798.34). A deeper investigation into promotions or campaigns during this period could help replicate success.
2. **Top Country:** The United States generated 79% of total revenue ($35,639). Targeted marketing efforts should focus on this market.
3. **Top Customers:** Five high-value customers were identified, but only one (Brenn Dundredge) is enrolled in the loyalty program. Targeting the remaining top customers with incentives could boost retention.
4. **Popular Product:** Excelsa beans led in total sales ($6,112). Promotions bundling Excelsa with underperforming beans could balance inventory and boost revenue.

---

## **Files in Repository**
1. Coffee_Sales_Dashboard.xlsx
Includes cleaned data, pivot tables, and the interactive dashboard.
2. Coffee_Sales_Report.docx
Detailed written report with analysis and recommendations.
3. Coffee_Sales_Dashboard_Screenshot.png
A visual preview of the final interactive dashboard.

## **Future Improvements**
1. Expand analysis to explore potential seasonality or trends over time.
2. Incorporate customer feedback data for qualitative insights.
3. Perform profitability analysis by including costs.

---
Inspired by Mo Chen's YouTube tutorial.

