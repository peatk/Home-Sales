## Home Sales Data Analysis with SparkSQL
This project focuses on analyzing home sales data using SparkSQL. The dataset provided contains information about home sales, and various queries are performed to derive key metrics. The tasks include creating temporary views, partitioning data, caching tables, and analyzing query runtimes.

#### Objectives
Find Avg Price for Four-bedroom Houses: Calculate the average price for a four-bedroom house sold for each year.
Determine the average price of homes for each year they were built, with three bedrooms and three bathrooms.
Find the average price of homes for each year they were built, meeting specific criteria (three bedrooms, three bathrooms, two floors, and at least 2,000 square feet).
Calculate the average price of homes per "view" rating with an average home price greater than or equal to $350,000, including query runtime.
Cache the home_sales temporary table, validate the cache, and compare query runtime before and after caching.
Partition the home sales dataset by the "date_built" field, read the formatted parquet data, and create a temporary table for it.
Run the query from step 4 on the parquet temporary table and compute the runtime.
Uncache the home_sales temporary table and verify the uncaching using PySpark.
