# Adidas-Sales-Analysis

This project presents a comprehensive sales analysis for a fictional Superstore using SQL and Power BI. It showcases how to clean, process, analyze, and visualize sales data to derive meaningful business insights and inform strategic decision-making.

🧾 Project Overview
The objective of this project is to analyze the Superstore sales data to understand customer behavior, product performance, profit trends, and regional variations. SQL is used for data cleaning, aggregation, and deriving KPIs. Power BI is used to build an interactive dashboard to visualize trends and insights.

🛠️ Tools Used
SQL Server — For querying, aggregation, and KPI extraction
👉 SQL Code
Power BI — For data visualization and dashboarding
👉 Dashboard Screenshot
Excel — Raw dataset in spreadsheet format
👉 Dataset File
📂 Dataset Description
The dataset contains transactional sales data for a retail store, including the following columns:

Column Name	Description
Order ID	Unique identifier for each order
Order Date	Date the order was placed
Ship Date	Date the order was shipped
Ship Mode	Shipping category (Standard, Second Class, etc.)
Customer ID	Unique ID for customers
Customer Name	Name of the customer
Segment	Customer type (Consumer, Corporate, Home Office)
Country/Region/City/State	Location data
Product ID	Unique identifier for products
Category	Product category
Sub-Category	Product sub-category
Product Name	Name of the product
Sales	Total sales amount
Quantity	Quantity sold
Discount	Discount applied
Profit	Profit gained/lost
❓ Questions Answered Using SQL
✅ Basic Queries:
Total sales, profit, and quantity
Unique values in categories, segments, ship modes
Monthly & yearly sales summary
Top-selling products by quantity and sales
Customers who ordered only once
🔁 Intermediate Queries:
Sales and profit by region, category, and segment
Discount impact on profitability
Sales by sub-category and product
Profit margin % by category
Shipping mode usage frequency
🔍 Advanced Queries:
Monthly growth rate using LAG() window function
Top profitable product by region using RANK()
Bottom 10 loss-making products
Trend of customer orders over time
Advanced customer segmentation by order count
📈 Key Insights
📦 Technology category generated the highest sales overall.
💰 Profit margins are highest in the Office Supplies segment.
🌎 The West region outperformed other regions in both sales and profit.
📉 Some products consistently lead to losses and need review.
🚚 Standard Class is the most used ship mode, covering nearly 59% of total orders.
📅 Sales peak during November and December, suggesting holiday season surges.
📉 Discounts above 30% often result in negative profits.
✅ Power BI Dashboard Highlights
Sales & profit breakdown by Category, Region, and Quarter
Monthly sales trend with comparative quantity movement
Interactive filters for Region, Year, and Segment
Top and bottom products by sales/profit
Relationship visualization between Sales and Profit
Donut charts and treemaps for quick glances
📍 See Power BI dashboard screenshots here.

🏁 Conclusion
This project successfully demonstrates the power of combining SQL and Power BI for business analytics. It reveals vital insights on sales performance, customer behavior, discount efficiency, and regional trends. These insights can be leveraged for better inventory management, targeted marketing, and profit optimization.
