🛒 Grocery Store Sales Analysis

📌 Project Overview

This project analyzes grocery store sales data for FoodYum, a U.S.-based grocery store chain. The objective is to ensure that all product categories include items at various price points, allowing the store to cater to a broad customer base. The analysis includes data cleaning, validation, and querying to support business decision-making.

📊 Dataset Description

The data is available in the products table, which contains customer purchase records for the last full year of the loyalty program.

Columns:

Column Name	Description
product_id	Unique product identifier.
product_type	Product category (Produce, Meat, Dairy, Bakery, Snacks). Missing values are replaced with "Unknown".
brand	Brand of the product. Missing values are replaced with "Unknown".
weight	Product weight (grams). Missing values are replaced with the median weight.
price	Product price (USD). Missing values are replaced with the median price.
average_units_sold	Average units sold per month. Missing values are replaced with 0.
year_added	Year the product was added. Missing values are replaced with 2022.
stock_location	Warehouse location (A, B, C, or D). Missing values are replaced with "Unknown".


🚀 Technologies Used

SQL for querying and data extraction.

Jupyter Notebook for analysis and visualization.

📌 How to Use

Clone this repository:

bash
Copy
Edit

git clone https://github.com/yourusername/grocery-store-sales.git

Open the Jupyter Notebook and run the queries.

Modify SQL queries to explore additional insights.

📩 Contact
For any inquiries, feel free to reach out!
