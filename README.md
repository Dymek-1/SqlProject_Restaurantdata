# SqlProject_Restaurantdata

📌 Project Overview
This project is a SQL-based analysis of restaurant order data. The goal is to identify popular menu items, uncover ordering patterns, and analyze customer behavior using a relational database of menu items and order details.

🧰 Tech Stack
MySQL – database creation, data querying & analysis

SQL – joins, aggregations, filtering, ordering

📂 Project Structure
File	Description
create_restaurant_db.sql	Creates the restaurant database and required tables
menu_item.sql	Inserts data into the menu_items table
order_details.sql	Inserts data into the order_details table
Combined menu_items and order_details.sql	Contains queries to explore, join and analyze the data
restaurant_db_data_dictionary.csv	Column descriptions for all tables
🔍 Key Insights (examples)
Which dishes are ordered most frequently?

What is the total revenue by item and category?

Which menu items have the highest average price per order?

On average, how many items are in one order?

🚀 How to Use
Open the .sql files in MySQL Workbench or any SQL IDE

Run create_restaurant_db.sql to create the schema

Load data using menu_item.sql and order_details.sql

Explore the data using queries in Combined menu_items and order_details.sql

📊 Data Source
Data used in this project is part of a learning exercise inspired by public YouTube tutorials and synthetic datasets.
