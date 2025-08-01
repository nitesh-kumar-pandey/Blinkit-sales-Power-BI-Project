# Blinkit Sales Analytics Dashboard – Project Documentation

### 1. Project Overview
This Power BI project analyzes Blinkit's sales data to visualize key performance metrics, identify sales trends, and evaluate contributing factors such as outlet type, size, location, and product categories. The dashboard helps in tracking total sales, average sales, number of items sold, and customer ratings.
________________________________________
### 2. Objectives
•	Monitor total and average sales performance.
•	Compare sales by outlet type, outlet size, and outlet location.
•	Analyze product-level performance by item type and fat content.
•	Understand how establishment year affects sales.
•	Provide a filterable, interactive dashboard for data-driven business decisions.
________________________________________
### 3. Data Sources
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
### 4. Key Metrics & KPIs
•	Total Sales: Sum of all sales transactions.
•	Average Sales: Mean sales per item.
•	Number of Items Sold: Total count of items.
•	Average Rating: Mean customer rating.
•	Item Visibility: Proportion of item display space.
________________________________________
### 5. Dashboard Components
&emsp;•	Summary Cards:<br>
&emsp;&emsp;o	Total Sales<br>
&emsp;&emsp;o	Average Sales<br>
&emsp;&emsp;o	Number of Items<br>
&emsp;&emsp;o	Average Rating<br>
&emsp;•	Visualizations:<br>
&emsp;&emsp;o	Sales by Fat Content: Donut chart dividing Low Fat vs. Regular.<br>
&emsp;&emsp;o	Sales by Item Type: Horizontal bar chart of total sales by category.<br>
&emsp;&emsp;o	Sales by Outlet Size: Donut chart showing Medium, Small, High sales contribution.<br>
&emsp;&emsp;o	Sales by Outlet Location: Bar chart showing Tier-wise performance.<br>
&emsp;&emsp;o	Sales Trend by Establishment Year: Line chart showing sales growth over years.<br>
&emsp;&emsp;o	Outlet Type Table: Table showing Total Sales, Number of Items, Average Sales, Ratings, and Item Visibility.<br>
&emsp;•	Filter Panel:<br>
&emsp;&emsp;o	Outlet Location Type<br>
&emsp;&emsp;o	Outlet Size<br>
&emsp;&emsp;o	Item Type<br>
________________________________________
### 6. Tools & Technologies<br>
&emsp;•	Power BI Desktop<br>
&emsp;•	Power Query (ETL for cleaning and transforming data)<br>
&emsp;•	DAX (Data Analysis Expressions) for calculated columns/measures<br>
&emsp;•	Excel/Database as source files<br>
________________________________________
### 7. Insights<br>
&emsp;•	Tier 3 outlets generate the highest sales.<br>
&emsp;•	Medium-sized outlets contribute the largest portion of total revenue.<br>
&emsp;•	"Snack Foods" and "Fruits & Vegetables" are top-selling categories.<br>
&emsp;•	Older outlet establishments show fluctuating sales trends.<br>
________________________________________
### 8. Future Enhancements<br>
&emsp;•	Add forecasting for future sales trends.<br>
&emsp;•	Drill-through to item-level profitability.<br>
&emsp;•	Include regional-level geographic mapping.<br>
&emsp;•	Automate report refresh using scheduled data updates.<br>
