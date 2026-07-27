# Sales-Analytics-Dashboard


## Problem Statement

This dashboard helps **ElectroHub** analyze its sales performance and make data-driven business decisions. It enables stakeholders to identify top and bottom performing products, monitor sales trends, compare sales across different time periods, evaluate discount strategies, and analyze customer purchasing behavior.

Using this dashboard, management can quickly identify profitable products, low-performing products, regional sales distribution, and sales trends over different time periods. Interactive filters allow users to drill down into product, customer, promotion, and date-level details for better business insights.

The dashboard answers the following business questions:

- Which are the Top 5 and Bottom 5 products based on Sales, Profit, and Quantity Sold?
- How do sales trends vary daily, monthly, quarterly, and annually?
- What is the relationship between Sales and Profit?
- How do Sales, Profit, and Quantity Sold compare between two different periods?
- What is the average discount offered in each discount category?
- How many total orders have been placed?
- How can users dynamically filter order-level information?
- Which cities generate the highest sales?

---

# Steps Followed

- Step 1 : Loaded the sales dataset into Power BI Desktop.

- Step 2 : Opened Power Query Editor and inspected the dataset using:

  - Column Quality
  - Column Distribution
  - Column Profile

- Step 3 : Changed profiling option to **Based on Entire Dataset** for complete data analysis.

- Step 4 : Verified data types and cleaned unnecessary columns.

- Step 5 : Checked for duplicate records, blank values, and inconsistencies before loading the dataset.

- Step 6 : Designed a **Star Schema** by creating relationships between the Fact Table and Dimension Tables.

- Step 7 : Created separate Date Tables for advanced time intelligence calculations.

- Step 8 : Built DAX Measures including:

```DAX
Total Sales =
SUM('Fact Table'[Sales])

Total Profit =
SUM('Fact Table'[Profit])

Quantity Sold =
SUM('Fact Table'[Units Sold])

Net Sales =
SUM('Fact Table'[Net Sales])
```

- Step 9 : Created additional DAX measures using:

```
CALCULATE()
USERELATIONSHIP()
ALL()
SUM()
FILTER()
```

to perform advanced date comparisons and KPI calculations.

- Step 10 : Created KPI Cards for:

- Total Sales
- Net Sales
- Total Profit
- Quantity Sold
- Total Orders

- Step 11 : Added interactive slicers for:

- Product
- Date
- Customer ID
- Promotion Category

- Step 12 : Created visualizations including:

- Line Chart
- Clustered Bar Chart
- Scatter Plot
- Map Visual
- Table Visual
- KPI Cards

- Step 13 : Built a dashboard for identifying Top 5 and Bottom 5 Products based on:

- Sales
- Profit
- Quantity Sold

- Step 14 : Created a Sales Trend Dashboard for analyzing:

- Daily Sales
- Monthly Sales
- Quarterly Sales
- Yearly Sales

- Step 15 : Built a Scatter Chart to analyze the relationship between Sales and Profit.

- Step 16 : Created comparison visuals allowing users to compare:

- Sales
- Profit
- Quantity Sold

between two selected periods.

- Step 17 : Designed a detailed transaction report displaying:

- Sales
- Profit
- Discount
- Net Sales
- Customer Information
- Product Information

with interactive filtering.

- Step 18 : Added a Map Visual to analyze city-wise sales performance.

- Step 19 : Applied a professional dashboard theme with consistent colors, icons, and formatting.

- Step 20 : Enabled drill-down, cross-filtering, and interactive report navigation.

- Step 21 : Saved the report as a Power BI (.pbix) project.

---

# Dashboard Snapshot

## Overview Dashboard

<img width="1379" height="747" alt="Image" src="https://github.com/user-attachments/assets/e11cc7cb-d7a1-4024-81f6-8cbc09e4ea37" />

---

## Top & Bottom 5 Products
<img width="1176" height="718" alt="Image" src="https://github.com/user-attachments/assets/6b4a635c-7313-4ade-80f9-f51798dbf238" />

---

## Sales Trend Dashboard
<img width="1167" height="713" alt="Image" src="https://github.com/user-attachments/assets/16615c91-2c15-45b2-9955-0ea1953e2bad" />

---

## Detailed Report

<img width="1142" height="661" alt="Image" src="https://github.com/user-attachments/assets/22de1a2a-60c0-4fda-8eb5-727a80cfa583" />

---

# Insights

The dashboard provides valuable business insights including:

### [1] Product Performance

- Identify Top 5 products by Sales.
- Identify Bottom 5 products by Sales.
- Identify Top 5 products by Profit.
- Identify Bottom 5 products by Profit.
- Compare products based on Quantity Sold.

---

### [2] Sales Trend Analysis

Analyze sales across:

- Daily
- Monthly
- Quarterly
- Annually

to identify seasonal trends and business growth.

---

### [3] Sales vs Profit

Analyze the relationship between Sales and Profit to identify highly profitable and low-margin products.

---

### [4] Period Comparison

Users can compare:

- Sales
- Profit
- Quantity Sold

between any two selected periods for better performance analysis.

---

### [5] Discount Analysis

Analyze average discounts across different discount categories to understand promotional effectiveness.

---

### [6] Order Analysis

Monitor:

- Total Orders
- Net Sales
- Profit
- Discount

for every order using dynamic filters.

---

### [7] Geographic Analysis

Identify cities contributing the highest sales and compare regional business performance.

---

### [8] Interactive Dashboard Features

- Dynamic Slicers
- Drill Down
- Cross Filtering
- Interactive KPIs
- Responsive Visualizations

allow users to explore business data efficiently.

---

# Tools & Technologies Used

- Microsoft Power BI
- Power Query
- DAX (Data Analysis Expressions)
- Star Schema Data Modeling
- Excel Dataset

---

# Skills Demonstrated

- Data Cleaning
- Data Transformation
- Data Modeling
- DAX Calculations
- Power Query
- Dashboard Design
- KPI Development
- Business Intelligence
- Data Visualization
- Analytical Thinking

---

# Author

**Ankit Jhuria**

B.Tech Electrical Engineering

National Institute of Technology Silchar

GitHub : [https://github.com/yourusername](https://github.com/ankitjhuria159)

LinkedIn : [https://linkedin.com/in/yourprofile](https://www.linkedin.com/in/ankit-jhuria-2aa293291/)
