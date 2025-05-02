# task7
Use Python to create a database
– You used sqlite3.connect("sales_data.db") to automatically create a small SQLite database — no setup needed!

Create a sales table
– You defined columns like product, quantity, and price to store sample sales records.

Insert multiple rows of dummy sales data
– Using executemany() and ?, ?, ? placeholders, you safely added product info like apples, bananas, grapes, and mangoes.

Write and run an SQL query in Python
– You grouped sales by product to calculate total quantity and total revenue using:

sql

SELECT product, SUM(quantity), SUM(quantity * price)
Load SQL results into a Pandas DataFrame
– You viewed the result as a clean table using pd.read_sql_query().

Visualize sales with a bar chart using Matplotlib
– You plotted revenue by product in a beautiful bar chart and even saved it as sales_chart.png.

