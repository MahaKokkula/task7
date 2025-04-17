Project Overview
The script performs the following tasks:

Creates an SQLite database (sales_data.db) if it doesn't already exist.

Creates a sales table to store product sales data.

Inserts sample sales data into the table.

Runs SQL queries to calculate the total quantity sold and total revenue per product.

Displays the summarized data in both text format (using pandas) and visualized as a bar chart (using matplotlib).

Requirements
Ensure you have the following Python libraries installed:
sqlite3 (This is built into Python)
pandas
matplotlib
Files
sales_data.db: SQLite database file that stores the sales data.

sales_data_analysis.py: Python script that:

Connects to the SQLite database.

Creates the sales table.
Inserts sample sales data into the table.
Runs SQL queries to aggregate sales data.
Displays the results as a DataFrame and a bar chart.
