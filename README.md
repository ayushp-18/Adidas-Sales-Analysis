# Adidas Sales Analysis
This project presents a comprehensive sales analysis for a fictional Superstore using SQL and Power BI. It demonstrates the complete process of cleaning, processing, analyzing, and visualizing sales data to generate actionable business insights that support strategic decision-making.

## Project Overview
The objective of this project is to analyze Superstore sales data to understand customer behavior, product performance, profitability trends, and regional variations.  
SQL was used for data cleaning, aggregation, and KPI derivation, while Power BI was employed to develop an interactive dashboard for visualizing key trends and insights.

## Tools Used
- **SQL Server:** For querying, data aggregation, and KPI extraction  
- **Power BI:** For data visualization and dashboard creation  
- **Excel:** For storing and managing the raw dataset  

## Dataset Description
The dataset contains transactional sales information for a retail store. The major columns include:

| Column Name | Description |
|--------------|-------------|
| Order ID | Unique identifier for each order |
| Order Date | Date the order was placed |
| Ship Date | Date the order was shipped |
| Ship Mode | Shipping category (Standard, Second Class, etc.) |
| Customer ID | Unique identifier for each customer |
| Customer Name | Name of the customer |
| Segment | Customer type (Consumer, Corporate, Home Office) |
| Country / Region / City / State | Geographical information |
| Product ID | Unique identifier for each product |
| Category | Product category |
| Sub-Category | Product sub-category |
| Product Name | Name of the product |
| Sales | Total sales amount |
| Quantity | Number of items sold |
| Discount | Discount applied |
| Profit | Profit earned or lost |

## SQL Analysis

### Basic Queries
- Calculation of total sales, profit, and quantity  
- Identification of unique categories, segments, and ship modes  
- Monthly and yearly sales summaries  
- Top-selling products by sales and quantity  
- Identification of customers with single transactions  

### Intermediate Queries
- Sales and profit by region, category, and segment  
- Analysis of discount impact on profitability  
- Sales performance by sub-category and product  
- Calculation of profit margin percentage by category  
- Frequency analysis of shipping modes  

### Advanced Queries
- Monthly growth rate using window functions (LAG)  
- Top profitable products by region using RANK()  
- Bottom 10 loss-making products  
- Order trend analysis over time  
- Customer segmentation based on order frequency  

## Key Insights
- The **Technology** category generated the highest total sales.  
- **Office Supplies** recorded the highest profit margins.  
- The **West** region outperformed all others in both sales and profit.  
- Several products consistently resulted in losses and require further review.  
- **Standard Class** shipping mode accounted for nearly 59% of all orders.  
- Sales peaked in **November and December**, reflecting holiday demand.  
- Discounts exceeding **30%** frequently led to negative profits.  

## Power BI Dashboard Highlights
- Sales and profit breakdown by Category, Region, and Quarter  
- Monthly sales trends with comparative quantity movements  
- Interactive filters for Region, Year, and Segment  
- Top and bottom products by sales and profit  
- Correlation visualization between Sales and Profit  
- Visual summaries using donut charts and treemaps  

## Conclusion
This project demonstrates how SQL and Power BI can be effectively integrated to perform end-to-end business analytics. The analysis provides valuable insights into sales performance, customer patterns, discount strategies, and regional trends. These insights can guide data-driven decisions for inventory management, marketing strategies, and overall profitability improvement.
