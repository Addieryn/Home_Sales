# Home_Sales

In this challenge, you'll use your knowledge of SparkSQL to determine key metrics about home sales data. Then you'll use Spark to create temporary views, partition the data, cache and uncache a temporary table, and verify that the table has been uncached. 
## Before You Begin
Create a new repository for this project called, Home_Sales. Do not add this homework to an existing repository. <br>
Clone the new repository to your computer. <br>
Push your changes to GitHub. 
## Files
Download the following files to help you get started: <br>
Module 22 Challenge files Links to an external site. 
## Instructions
Rename the Home_Sales_starter_code.ipynb file as Home_Sales.ipynb. <br>
Import the necessary PySpark SQL functions for this assignment. <br>
Read the home_sales_revised.csv data in the starter code into a Spark DataFrame. <br>
Create a temporary table called home_sales. <br>
Answer the following questions using SparkSQL: <br>
What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places. <br>
What is the average price of a home for each year the home was built, that has three bedrooms and three bathrooms? Round off your answer to two decimal places. <br>
What is the average price of a home for each year the home was built, that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? <br>
Round off your answer to two decimal places. <br>
What is the average price of a home per "view" rating having an average home price greater than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places. <br>
Cache your temporary table home_sales. <br>
Check if your temporary table is cached. <br>
Using the cached data, run the last query that calculates the average price of a home per "view" rating having an average home price greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime. <br>
Partition by the "date_built" field on the formatted parquet home sales data. <br>
Create a temporary table for the parquet data. <br>
Run the last query that calculates the average price of a home per "view" rating having an average home price greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime. <br>
Uncache the home_sales temporary table. <br>
Verify that the home_sales temporary table is uncached using PySpark. <br>
Download your Home_Sales.ipynb file and upload it into your "Home_Sales" GitHub repository. 
## Support and Resources
Your instructional team will provide support during classes and office hours. You will also have access to learning assistants and tutors to help you with topics as needed. Make sure to take advantage of these resources as you collaborate with your partner on this project. 
## Requirements
A Spark DataFrame is created from the dataset. (5 points) <br>
A temporary table of the original DataFrame is created. (10 points) <br>
A query is written that returns the average price, rounded to two decimal places, for a fourbedroom house that was sold in each year. (5 points) <br>
A query is written that returns the average price, rounded to two decimal places, of a home that has three bedrooms and three bathrooms for each year the home was built. (5 points) <br>
A query is written that returns the average price of a home with three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet for each year the home was built rounded to two decimal places. (5 points) <br>
A query is written that returns the average price of a home per "view" rating having an average home price greater than or equal to $350,000, rounded to two decimal places. (The output shows the run time for this query.) (10 points) <br>
A cache of the temporary "home_sales" table is created and validated. (10 points) <br>
The query from step 6 is run on the cached temporary table, and the run time is computed. (10 points) <br>
A partition of the home sales dataset by the "date_built" field is created, and the formatted parquet data is read. (10 points) <br>
A temporary table of the parquet data is created. (10 points) <br>
The query from step 6 is run on the parquet temporary table, and the run time is computed. (10 points) <br>
The "home_sales" temporary table is uncached and verified. (10 points) 
