# Decathlon Sales & Customer Analytics Dashboard

## Project Title
**Decathlon Sales & Customer Analytics Dashboard Using Microsoft Excel**

## Project Overview

This project is an interactive **Sales & Customer Analytics Dashboard created entirely in Microsoft Excel** using a synthetic Decathlon-style retail dataset containing **30,000 orders**.

The dashboard converts raw sales and customer data into an easy-to-understand business report. It provides a high-level view of sales performance, order volume, customer base, average order value, sports performance, product categories, customer retention, and gender-wise sales.

The project is designed as a **data analytics and Excel dashboard portfolio project** to demonstrate practical skills in data cleaning, data analysis, Excel formulas, PivotTables, charts, KPI reporting, and dashboard design.

> **Disclaimer:** The dataset is synthetic and created for educational/portfolio purposes. This project is not official Decathlon data and is not affiliated with or endorsed by Decathlon.

---

## Dashboard Preview

![Decathlon Sales & Customer Analytics Dashboard](assets/dashboard.png)

---

## Key Performance Indicators

The dashboard currently displays the following major KPIs:

| KPI | Current Value |
|---|---:|
| **Total Sales** | **₹36.7 Cr** |
| **Total Orders** | **30,000** |
| **Total Customers** | **8,998** |
| **Average Order Value** | **₹12,236** |

The dashboard also provides year-wise filtering for **2024, 2025, and 2026**.

---

## Dashboard Sections

### 1. Total Sales
Displays the overall sales generated from the dataset and provides a quick view of sales growth.

### 2. Total Orders
Shows the total number of orders recorded in the dataset.

### 3. Total Customers
Displays the number of unique customers represented in the dataset.

### 4. Average Order Value
Shows the average amount spent per order.

### 5. Top 5 Sports Type

The dashboard highlights the top five sports based on sales performance:

- Cycling
- Gym
- Hiking
- Outdoor
- Running

For each sport, the dashboard displays its sales contribution and order volume.

### 6. Sales Over Time

A line chart is used to analyze monthly sales performance and identify changes in sales across the selected period.

### 7. Sales by Product Category

A donut chart displays the contribution of different product categories to overall sales.

### 8. Customer Retention Rate

The dashboard contains a monthly customer retention trend to understand how customer retention changes over time.

### 9. Sales by Gender

A donut chart provides a comparison of sales distribution between male and female customers.

### 10. Year Filter

The dashboard contains a year selector that allows users to analyze the data for:

- 2024
- 2025
- 2026

---

## Dataset

The project uses a synthetic retail dataset containing **30,000 records**.

The dataset includes information related to:

- Orders
- Customers
- Products
- Sports
- Sales
- Discounts
- Stores
- Payment methods
- Delivery
- Customer ratings
- Returns
- Promotions
- Date and time

### Important Data Fields

| Field | Purpose |
|---|---|
| `Order_ID` | Unique order identifier |
| `Order_Date` | Date on which the order was placed |
| `Order_Time` | Time of order |
| `Customer_ID` | Unique customer identifier |
| `Customer_Name` | Customer name |
| `Gender` | Customer gender |
| `Age` | Customer age |
| `Age_Group` | Customer age segment |
| `City` | Customer city |
| `State` | Customer state |
| `Membership_Type` | Customer membership level |
| `Customer_Segment` | Customer segment |
| `Product_ID` | Product identifier |
| `Product_Name` | Product name |
| `Product_Category` | Product category |
| `Brand` | Product brand |
| `Sport_Type` | Associated sport |
| `Quantity` | Quantity purchased |
| `Unit_Price` | Price per unit |
| `Discount_Percent` | Discount percentage |
| `Discount_Amount` | Discount value |
| `Sales_Amount` | Sales before final adjustments |
| `Final_Amount` | Final transaction amount |
| `Cost_Price` | Product cost |
| `Profit` | Profit generated |
| `Store_ID` | Store identifier |
| `Store_Name` | Store name |
| `Sales_Channel` | Online/offline sales channel |
| `Payment_Method` | Payment method |
| `Delivery_Type` | Delivery method |
| `Delivery_Days` | Delivery duration |
| `Customer_Rating` | Customer rating |
| `Return_Status` | Return information |
| `Return_Reason` | Reason for return |
| `Promotion_Campaign` | Promotion/campaign |
| `Quarter` | Quarter of order |
| `Month` | Month of order |
| `Year` | Year of order |

---

## Excel Skills Used

This project focuses specifically on **Microsoft Excel**.

### Data Analysis
- Data cleaning and preparation
- Sorting and filtering
- Excel Tables
- Data aggregation
- KPI calculations
- Date-based analysis

### PivotTables
PivotTables were used to summarize and analyze:

- Sales
- Orders
- Customers
- Sports
- Product categories
- Gender
- Monthly performance
- Customer retention

### Charts & Visualization
The dashboard uses Excel visualizations including:

- KPI cards
- Line charts
- Donut charts
- Image-based sports cards
- Trend analysis
- Interactive filtering

### Excel IMAGE Function

The dashboard includes sports images using Excel's `IMAGE()` functionality, allowing sports-related visuals to be displayed directly inside the workbook.

---

## Business Questions Answered

The dashboard helps answer important business questions such as:

1. What is the total sales generated?
2. How many orders were placed?
3. How many unique customers are there?
4. What is the average order value?
5. Which sports generate the highest sales?
6. Which sports have the highest order volume?
7. How do sales change month by month?
8. Which product categories contribute the most to sales?
9. What is the customer retention trend?
10. How are sales distributed by gender?
11. How does performance change between 2024, 2025, and 2026?

---

## Key Insights

Based on the current dashboard:

- The dataset contains **30,000 orders**.
- There are **8,998 unique customers**.
- Total sales are approximately **₹36.7 Crore**.
- Average order value is approximately **₹12,236**.
- The dashboard covers **2024–2026**.
- **Cycling** is the leading sport type by sales in the current dashboard.
- The dashboard combines sales, customer, product, sports, and retention analysis in one view.

---

## Project Workflow

```text
Raw Excel Dataset
       ↓
Data Cleaning & Preparation
       ↓
Data Analysis
       ↓
PivotTables / Calculations
       ↓
Charts & Visualizations
       ↓
Interactive Dashboard
       ↓
Business Insights
```

---

## Project Structure

```text
decathlon-sales-customer-analytics-excel/
│
├── assets/
│   └── dashboard.png
│
├── data/
│   └── Decathlon_Synthetic_Data_30000.xlsx
│
├── README.md
└── LICENSE
```

---

## How to Use

1. Download the Excel workbook from this repository.
2. Open it in **Microsoft Excel 2024** or a compatible version.
3. Open the dashboard sheet.
4. Use the year filter to change the analysis period.
5. Explore the KPI cards and visualizations.
6. Refresh the PivotTables if the underlying dataset is modified.

---

## Future Improvements

Possible improvements for the next version include:

- Profit and profit-margin dashboard
- State/city-wise sales analysis
- Product-level performance analysis
- Customer segmentation dashboard
- Return-rate analysis
- Discount impact analysis
- Sales-channel comparison
- Payment-method analysis
- Advanced customer lifetime value analysis
- Automated data refresh

---

## Tools & Technologies

- **Microsoft Excel 2024**
- Excel Tables
- PivotTables
- PivotCharts
- Excel formulas
- `IMAGE()` function
- Slicers / Filters
- Data visualization

---

## Author

**Atharva Mankar**

This project was created as a portfolio project to demonstrate practical skills in **Microsoft Excel, data analysis, dashboard development, KPI reporting, and business intelligence**.

---

## License

This project is licensed under the **MIT License**.

See the `LICENSE` file for details.

The Decathlon name and trademarks belong to their respective owner. This is an independent educational/portfolio project using synthetic data.
