# Coffee-Sales-Excel-Dashboard
In this excel project: I gather, transform the data, analyze, and visualize it ending up with a dynamic and interactive dashboard

![image](https://github.com/salmaH4/Sales-Excel-Dashboard-for-Coffee-Orders/assets/110805003/22a33292-48f4-4052-b544-bc54d8a3b84a)


## Project walkthrough
- Gathering the data from multiple tables using XLOOKUP and INDEX MATCH
- Transforming and cleaning the data using nested IFS
- Insert pivot tables and pivot charts to bulid the dashboard
___

### Data gathering Process:
- I gathered the customer data table into the orders table using XLOOKUP
- I also gathered the products data table into the orders table using INDEX MATCH to be dynamic

### Data Cleaning and preparing Process:
- Handled missing values in the email column: by replacing zero values into null values using IF statement
- Adding a sales, coffee full name, Roast full type name
- for the size column I added "kg" in the format cells to be easier to understand
- format the sales and unit price columns in US dollars

### Data Visualization Process:
- Line Chart for "Total sales over time"
- Time line for "Order Date" with years and months
- Created 3 slices for "Roast Type Name", "Size", and "Loyality Card"
- Bar Chart for "Top Sales by country"
- Bar chart for "Top Sales by Customers"


