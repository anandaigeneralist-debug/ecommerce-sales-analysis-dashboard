# E-Commerce Sales Analysis Dashboard

## Project Overview

The **E-Commerce Sales Analysis Dashboard** is an interactive dashboard designed to analyze and monitor e-commerce business performance. It provides an overview of sales, quantity, products, orders, discounts, and average order value through key performance indicators (KPIs) and visualizations.

The dashboard helps users understand monthly sales trends, identify top-performing products and cities, compare sales channels, and evaluate category-wise quantity performance. Interactive filters allow users to explore the data by quarter, region, customer segment, and order status.

## Project Objectives

- Monitor overall e-commerce sales performance.
- Track total quantity sold, products, and orders.
- Understand average discount percentage and average order value.
- Analyze monthly sales trends.
- Identify top-performing products and cities.
- Compare quantity across sales channels and product categories.
- Explore business performance using interactive filters.

## Dataset Description

- **Dataset:** `Ecommerce_Dashboard_2000_Rows_Simple.xlsx`
- **Worksheet:** `Ecommerce_Sales`
- **Records:** 1,997 data rows
- **Columns:** 13
- **Period covered:** January 1, 2025 – December 31, 2025

### Dataset Columns

| Column | Description |
|---|---|
| `Order_ID` | Unique order identifier |
| `Order_Date` | Date on which the order was placed |
| `Product_Name` | Name of the product |
| `Category` | Product category |
| `Region` | Sales region |
| `City` | Customer/order city |
| `Sales_Channel` | Channel used to place the order |
| `Customer_Segment` | Customer type or segment |
| `Quantity` | Number of units ordered |
| `Unit_Price` | Price per unit |
| `Discount_Pct` | Discount percentage applied |
| `Net_Sales` | Sales value after discount |
| `Order_Status` | Current order status |

## Key Performance Indicators (KPIs)

The dashboard contains six main KPIs:

| KPI | Description |
|---|---|
| **1. Total Sales** | Sum of `Net_Sales` across all orders. |
| **2. Total Quantity** | Sum of the `Quantity` column. |
| **3. Total Products** | Count of distinct product names. |
| **4. Total Orders** | Count of unique order IDs. |
| **5. Average Discount %** | Average of the `Discount_Pct` column. |
| **6. Average Order Value (AOV)** | Total Sales divided by Total Orders. |

### Overall KPI Summary

The following values are calculated from the supplied dataset and are consistent with the dashboard's rounded KPI cards.

| KPI | Value |
|---|---:|
| Total Sales | 6.71M |
| Total Quantity | 2,958 (approximately 3K) |
| Total Products | 20 |
| Total Orders | 1,997 (approximately 2K) |
| Average Discount % | 9.90% |
| Average Order Value | 3.36K |

## Dashboard Visualizations

The dashboard includes the following charts:

1. **Total Value by Month** – A monthly trend chart showing how sales value changes throughout the year.
2. **Total Value by Product Name** – A horizontal bar chart comparing sales value across products and highlighting top-performing products.
3. **Total Value by City** – A city-wise comparison of sales value.
4. **Total Quantity by Sales Channel** – A doughnut chart showing the distribution of quantity across Marketplace, Website, and Mobile App.
5. **Total Quantity by Category** – A horizontal bar chart comparing quantities across product categories.

## Interactive Filters (Slicers)

Users can filter the dashboard using:

- **Quarter:** Qtr 1, Qtr 2, Qtr 3, and Qtr 4.
- **Region:** Central, East, North, South, and West.
- **Customer Segment:** Consumer, Corporate, and Small Business.
- **Order Status:** Cancelled, Delivered, Returned, and Shipped.

These filters make it possible to analyze business performance for selected time periods, regions, customer groups, and order statuses.

## Key Insights

- The business generated approximately **6.71 million** in net sales during 2025.
- The dataset contains **20 distinct products**.
- Total sales quantity is approximately **3,000 units**.
- The average discount across the dataset is approximately **9.90%**.
- The average order value is approximately **3.36K**.
- The monthly sales chart helps identify periods of higher and lower sales.
- Product-wise and city-wise charts help compare sales performance across products and locations.
- The sales-channel and category charts show how order quantities are distributed.

## Tools & Technologies

- **Microsoft Excel:** Source dataset.
- **Power BI:** Interactive dashboard and data visualization.

## Conclusion

This project demonstrates how e-commerce sales data can be transformed into an interactive business intelligence dashboard. By combining KPI cards, trend analysis, product and city comparisons, and interactive slicers, the dashboard makes it easier to monitor sales performance and explore business data.

The analysis can support data-driven decisions related to sales performance, product planning, regional performance, customer segments, and sales channels.

---

**Project:** E-Commerce Sales Analysis Dashboard  
**Dataset:** E-commerce Sales – 2025  
**Dashboard Type:** Interactive Business Intelligence Dashboard
