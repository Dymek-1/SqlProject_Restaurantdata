# SqlProject_Restaurantdata

📌 Project Overview
This project is a comprehensive analysis of restaurant order data using SQL and Power BI. The main goal is to identify popular menu items, analyze ordering patterns, and gain insights into customer behavior. The project involves building a relational database to store menu items and order details, performing data analysis using SQL queries, and visualizing the results with interactive dashboards in Power BI.

The database was created using MySQL, and the data was analyzed through joins, aggregations, filtering, and ordering. The project structure includes several SQL scripts for database creation, data insertion, and analysis. In addition, the visual aspect of the project was implemented in Power BI to make data insights more intuitive and accessible.

The visualizations created in Power BI include:

Top Ordered Dishes by Category (Bar Chart) – A visual representation of the most frequently ordered dishes, categorized by cuisine type (American, Asian, Italian, Mexican).

Category Share in Total Orders (Pie Chart) – Displays the percentage share of each category in the total number of orders.

Revenue Trend Over Time (Line Chart) – Shows the total revenue generated per month, highlighting seasonal patterns.

Order Volume by Day of the Week (Bar Chart) – Helps identify peak ordering days in the restaurant.

Heatmap: Orders by Day and Hour – Visualizes the busiest hours and days of the week to help optimize restaurant operations.

Average Order Value by Category (Column Chart) – Compares the average revenue per order across different categories, providing insights into which cuisine types are the most profitable.

Top 5 Dishes in Each Category (Stacked Bar Chart) – Shows the most popular dishes within each cuisine type, allowing for a detailed comparison.

The SQL part of the project is structured as follows:

create_restaurant_db.sql – Creates the restaurant database and necessary tables.

menu_item.sql – Populates the menu_items table with data.

order_details.sql – Populates the order_details table with data.

Combined menu_items and order_details.sql – Contains queries to join, explore, and analyze the data.

restaurant_db_data_dictionary.csv – Provides descriptions of the table columns.

Projekt_Restauracja_SQL.pbix – Power BI report containing interactive dashboards and visual insights.

The analysis addresses several key questions:

Which dishes are the most frequently ordered?

What is the total revenue by item and category?

Which menu items have the highest average price per order?

On average, how many items are included in one order?

What are the busiest times of the day and week for orders?

Which cuisine types generate the most revenue?
