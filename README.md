## Home Sales Data Analysis with SparkSQL
This project focuses on analyzing home sales data using SparkSQL. The dataset provided contains information about home sales, and various queries are performed to derive key metrics. The tasks include creating temporary views, partitioning data, caching tables, and analyzing query runtimes.

#### Files
Home_Sales_starter_code.ipynb: Initial notebook file provided with starter code.
home_sales_revised.csv: Dataset containing home sales data.
Getting Started
Clone the repository: git clone <repository_url>
Rename Home_Sales_starter_code.ipynb to Home_Sales.ipynb.
Import the necessary PySpark SQL functions.
Read the home_sales_revised.csv data into a Spark DataFrame.
Create a temporary table called home_sales.

#### Tasks
Average Price for Four-bedroom Houses: Calculate the average price for a four-bedroom house sold for each year.
Average Price of Homes by Year Built: Determine the average price of homes for each year they were built, with three bedrooms and three bathrooms.
Average Price of Specific Home Criteria by Year Built: Find the average price of homes for each year they were built, meeting specific criteria (three bedrooms, three bathrooms, two floors, and at least 2,000 square feet).
Average Price per View Rating: Calculate the average price of homes per "view" rating with an average home price greater than or equal to $350,000, including query runtime.
Caching and Query Runtime: Cache the home_sales temporary table, validate the cache, and compare query runtime before and after caching.
Partitioning and Parquet Data: Partition the home sales dataset by the "date_built" field, read the formatted parquet data, and create a temporary table for it.
Query Runtime on Parquet Data: Run the query from step 4 on the parquet temporary table and compute the runtime.
Uncaching and Verification: Uncache the home_sales temporary table and verify the uncaching using PySpark.
Evaluation
This project will be evaluated based on the following requirements:

Creation of Spark DataFrame from the dataset.
Creation of a temporary table of the original DataFrame.
Writing queries to compute average prices based on specific criteria.
Caching of the temporary table and validation.
Performance analysis before and after caching.
Partitioning of data and analysis on parquet data.
Proper uncaching and verification steps.
