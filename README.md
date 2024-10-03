# WalmartDataAnalytics
Tech Stack: Excel (external data source), MySQL Workbench

This repository contains a script for analyzing sales data from a Walmart store. The script performs various tasks, including:

* **Database Creation and Table Definition:**
    * Creates a database named `walmartSales` if it doesn't exist.
    * Defines a table named `sales` with relevant columns to store sales information.
* **Data Import (**Please Note:** This section assumes data is provided elsewhere)**
    * The script doesn't include the actual data import process. Modify this section to reflect your specific data import method (e.g., importing from a CSV file).
* **Data Analysis and Transformation:**
    * Adds derived columns: `time_of_day`, `day_name`, and `month_name`.
    * Performs various analytical queries to answer questions about the sales data, such as:
        * Number of unique cities, branches, and product lines.
        * Top-selling product lines by quantity and revenue.
        * Total revenue and COGS by month.
        * Highest revenue city and product line.
        * Average VAT and rating by product line.
        * Customer demographics and purchase behavior.
        * Sales trends based on time of day, day of week, and gender.
        * Comparison of sales performance across branches.
        * Identifying top customer types based on revenue and purchases.
* **(Optional) Data Visualization:** This script doesn't include data visualization. Consider using tools like Tableau or Python libraries (e.g., Matplotlib) to create charts and graphs for further analysis.

## Running the Script

**1. Prerequisites:**

- This script assumes you have a database management system (DBMS) like MySQL or PostgreSQL installed.
- You may need to modify the script depending on your specific DBMS syntax.

**2. Execution:**

- Copy the script into your desired location.
- Open a terminal or command prompt and navigate to the directory containing the script.
- Execute the script using the appropriate command for your DBMS (e.g., `mysql < script.sql` for MySQL).

**3. Data Import:**

- Modify the script's data import section to reflect your data source and import method.

**4. Exploration:**

- Review the script's comments and queries to understand the analysis performed.
- Modify existing queries or add your own to explore the data further.

[Medium Article](https://medium.com/@plalindia01/walmart-sales-analysis-a-case-study-3c204dd99fd1)

PS This is not my original work. This is rather an attempt at duplication for learning purposes.

This script provides a starting point for analyzing Walmart sales data. You can expand on it to answer more specific questions and gain deeper insights into sales trends and customer behavior.






