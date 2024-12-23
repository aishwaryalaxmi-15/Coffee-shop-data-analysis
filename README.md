# Coffee Shop Data Analysis - Mini Project (Excel)

## Project Overview

This project involves the analysis of sales data from a coffee shop using **Microsoft Excel**. The goal of the analysis is to gain insights into sales trends, product performance, customer preferences, and payment methods. The analysis was performed using Excel’s powerful data manipulation and visualization tools, such as pivot tables, charts, and conditional formatting.

---

## Project Objectives

- Identify the best-selling products at the coffee shop.
- Analyze sales trends over time.
- Determine the most preferred payment methods.
- Explore customer purchase behavior and segment sales by customer type.
- Provide actionable insights to improve sales strategies and customer experience.

---

## Tools & Technologies

- **Microsoft Excel**: Used for data analysis, manipulation, and visualization.
  - **Pivot Tables**: For summarizing data and aggregating sales information.
  - **Charts**: For visualizing sales trends, product popularity, and payment method distribution.
  - **Conditional Formatting**: To highlight key insights and trends in the data.

---

## Data Description

The dataset contains the following columns:

- **Order ID**: Unique identifier for each order.
- **Date**: Date when the order was placed.
- **Product Name**: The name of the product sold.
- **Price**: Price of each item sold.
- **Quantity Sold**: Number of units sold per product.
- **Customer Type**: The type of customer (e.g., Regular or New).
- **Payment Method**: Method of payment used (Cash, Card, etc.).

---

## Steps & Analysis

### 1. **Data Import & Cleaning**
   - The data was imported into Excel and cleaned to ensure that missing values were handled and the data was formatted correctly (e.g., Date as a date type).

### 2. **Total Sales Calculation**
   - A new column was added to calculate **Total Sales** using the formula:
     ```
     Total Sales = Price * Quantity Sold
     ```

### 3. **Sales by Product**
   - A **Pivot Table** was created to summarize the total quantity sold for each product. This helped in identifying the best-selling products.

### 4. **Sales Trends Over Time**
   - A **Pivot Table** was used to group sales by **Date**, and a **Line Chart** was generated to visualize how sales varied over time.

### 5. **Customer Type Analysis**
   - A **Pivot Table** was used to compare sales between **Regular** and **New** customers. This helped identify which customer type contributed the most to sales.

### 6. **Payment Method Distribution**
   - A **Pivot Table** was used to calculate the total sales for each payment method (e.g., Cash, Card). A **Pie Chart** was then created to visualize the proportion of each payment method.

### 7. **Product Performance**
   - A **Bar Chart** was created to visualize which products were the top performers in terms of quantity sold.

---

## Visualizations

- **Sales Trend (Line Chart)**: Displays the total sales over time, helping to identify sales patterns, peaks, and valleys.
- **Payment Method Distribution (Pie Chart)**: Shows the breakdown of sales by payment method, indicating which method is most preferred by customers.
- **Product Performance (Bar Chart)**: Compares sales performance by product, highlighting the best-sellers.
- **Customer Type Sales (Bar Chart)**: Analyzes sales performance between regular and new customers.

---

## Conclusion

- **Best-Selling Products**: The analysis identified the most popular products based on the quantity sold, helping focus on high-demand items.
- **Sales Trends**: The sales data revealed key trends over time, such as peak sales days or periods with slower sales.
- **Payment Methods**: The data showed that most customers prefer using [Payment Method], which could help optimize payment processes and customer experience.
- **Customer Insights**: The comparison between regular and new customers helped in understanding their behavior, suggesting targeted marketing efforts.

---

## How to Use the Excel File

1. Open the **Coffee_Shop_Analysis.xlsx** file in Microsoft Excel.
2. Review the **Pivot Tables** and **Charts** created in the sheet.
3. You can modify the date range or filter by product or customer type to explore other insights.
