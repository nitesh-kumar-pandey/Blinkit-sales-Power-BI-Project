# Blinkit Sales Analytics Dashboard – Project Documentation

1. Project Overview
This Power BI project analyzes Blinkit's sales data to visualize key performance metrics, identify sales trends, and evaluate contributing factors such as outlet type, size, location, and product categories. The dashboard helps in tracking total sales, average sales, number of items sold, and customer ratings.
________________________________________
2. Objectives
•	Monitor total and average sales performance.
•	Compare sales by outlet type, outlet size, and outlet location.
•	Analyze product-level performance by item type and fat content.
•	Understand how establishment year affects sales.
•	Provide a filterable, interactive dashboard for data-driven business decisions.
________________________________________
3. Data Sources
•	Primary Source: Blinkit historical sales dataset (Excel/CSV/Database).
•	Key Data Columns:
o	Item Type
o	Fat Content
o	Outlet Type
o	Outlet Size
o	Outlet Location Type (Tier 1, Tier 2, Tier 3)
o	Outlet Establishment Year
o	Item Sales
o	Item Rating
o	Item Visibility
________________________________________
4. Key Metrics & KPIs
•	Total Sales: Sum of all sales transactions.
•	Average Sales: Mean sales per item.
•	Number of Items Sold: Total count of items.
•	Average Rating: Mean customer rating.
•	Item Visibility: Proportion of item display space.
________________________________________
5. Dashboard Components
•	Summary Cards:
o	Total Sales
o	Average Sales
o	Number of Items
o	Average Rating
•	Visualizations:
o	Sales by Fat Content: Donut chart dividing Low Fat vs. Regular.
o	Sales by Item Type: Horizontal bar chart of total sales by category.
o	Sales by Outlet Size: Donut chart showing Medium, Small, High sales contribution.
o	Sales by Outlet Location: Bar chart showing Tier-wise performance.
o	Sales Trend by Establishment Year: Line chart showing sales growth over years.
o	Outlet Type Table: Table showing Total Sales, Number of Items, Average Sales, Ratings, and Item Visibility.
•	Filter Panel:
o	Outlet Location Type
o	Outlet Size
o	Item Type
________________________________________
6. Tools & Technologies
•	Power BI Desktop
•	Power Query (ETL for cleaning and transforming data)
•	DAX (Data Analysis Expressions) for calculated columns/measures
•	Excel/Database as source files
________________________________________
7. Insights
•	Tier 3 outlets generate the highest sales.
•	Medium-sized outlets contribute the largest portion of total revenue.
•	"Snack Foods" and "Fruits & Vegetables" are top-selling categories.
•	Older outlet establishments show fluctuating sales trends.
________________________________________
8. Future Enhancements
•	Add forecasting for future sales trends.
•	Drill-through to item-level profitability.
•	Include regional-level geographic mapping.
•	Automate report refresh using scheduled data updates.
