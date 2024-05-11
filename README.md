# Home_Sales
Module 22 Challenge Big Data
Student Name: Thotadamoole Shreenidhi
In this challenge, I was able to use my knowledge of SparkSQL to determine key metrics about home sales data. Then I used Spark to create temporary views, partition the data, cache and uncache a temporary table, and verify that the table has been uncached.
Few Observations:
With out the cache, querry took --- 0.9203519821166992 seconds ---
After creating the cache querry took --- 0.6018469333648682 seconds ---
After partetioning the parquet home sales data, querry took --- 0.49892497062683105 seconds ---

Following questions were answered using SparkSQL:

What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.

What is the average price of a home for each year the home was built, that has three bedrooms and three bathrooms? Round off your answer to two decimal places.

What is the average price of a home for each year the home was built, that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.

What is the average price of a home per "view" rating having an average home price greater than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.

Following activities were carried out using SparkSQL:
Cache your temporary table home_sales.

Check if your temporary table is cached.

Using the cached data, run the last query that calculates the average price of a home per "view" rating having an average home price greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.

Partition by the "date_built" field on the formatted parquet home sales data.

Create a temporary table for the parquet data.

Run the last query that calculates the average price of a home per "view" rating having an average home price greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.

Uncache the home_sales temporary table.

Verify that the home_sales temporary table is uncached using PySpark.
