# Home_Sales
An exercise in SQL queries of a CSV with Spark 

## Running the File
Included is a .ipynb file for use with Google Colab. To run the code, simply upload it onto their service and run it sequentially. All necessary dependencies, plugins, and files will load automatically. 

## Purpose
In addition to showing off example SQL queries, the main purpose of this file is comparing the result times for different methods of table storage. Box number 6 demonstrates a read off of a temporary table view, box number 9 includes a read off of a cached table, and box 13 reads off partitioned parquet data. For this particular exercise, the cached data performed the best, followed by the parquet. The temporary view performed the worst. While all of the queries were less than half a second, this could be a difference worth investigating further for especially large data sets.


