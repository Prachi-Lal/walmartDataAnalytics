# WalmartDataAnalytics
Tech Stack: Excel (external data source), MySQL Workbench

This repository contains a script for analyzing sales data from a Walmart store. The script performs various tasks, including:

* **Database Creation and Table Definition:**
    * Creates a database named `walmartSales` if it doesn't exist.
    * Defines a table named `sales` with relevant columns to store sales information.
* **Data Import**
    * Importing from a CSV file or Kaggle's [Walmart Recruiting - Store Sales Forecasting](https://www.kaggle.com/c/walmart-recruiting-store-sales-forecasting)
* **Data Analysis and Transformation:**
    * Adding derived columns: `time_of_day`, `day_name`, and `month_name`.
    * Performing various analytical queries to answer questions about the sales data, such as:
        * Number of unique cities, branches, and product lines.
        * Top-selling product lines by quantity and revenue.
        * Total revenue and COGS by month.
        * Highest revenue city and product line.
        * Average VAT and rating by product line.
        * Customer demographics and purchase behavior.
        * Sales trends based on time of day, day of week, and gender.
        * Comparison of sales performance across branches.
        * Identifying top customer types based on revenue and purchases.
          
## Running the Script

**1. Prerequisites:**

- Microsoft Excel
- MySQL WorkBench

**2. Exploration:**

- Review the script's comments and queries to understand the analysis performed.

[Medium Article](https://medium.com/@plalindia01/walmart-sales-analysis-a-case-study-3c204dd99fd1)

PS This is not my original work. This is rather an attempt at duplication for learning purposes.

This script provides a starting point for analyzing Walmart sales data. You can expand on it to answer more specific questions and gain deeper insights into sales trends and customer behavior.






