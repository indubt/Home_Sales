# Home_Sales
This project is created for the University of Minnesota = Data Visualization and Analytics Bootcamp - Module 22 BigData Challenge.

In this challenge, I used SparkSQL to determine key metrics about home sales data. Then, used Spark to create temporary views, partition the data, cache and uncache a temporary table, and verify that the table has been uncached.

### Contributor : Indu Bandi

# Instructions

1. Open [Home_Sales_colab.ipynb](Home_Sales_colab.ipynb) in the repo, in google colab

2. Import the necessary PySpark SQL functions for this assignment.

3. Read the home_sales_revised.csv data from AWS S3 bucket into a Spark DataFrame.

4. Create a temporary table called home_sales.

5. Used SparkSQL to answer the following questions:

    a. What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.

    b. What is the average price of a home for each year the home was built, that has three bedrooms and three bathrooms? Round off your answer to two decimal places.

    c. What is the average price of a home for each year the home was built, that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.

    d. What is the average price of a home per "view" rating having an average home price greater than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.

6. Cache temporary table homesales.

7. Check if temporary table is cached.

8. Using the cached data, run the last query that calculates the average price of a home per "view" rating having an average home price greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.

9. Partition by the "date_built" field on the formatted parquet home sales data.

10. Create a temporary table for the parquet data.

11. Run the last query that calculates the average price of a home per "view" rating having an average home price greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.

12. Uncache the homesales temporary table.

13. Verify that the homesales temporary table is uncached using PySpark.

## References

Class Materials