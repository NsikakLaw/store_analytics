# Store Database Insights and Analytics

This project was a recent work performed on a store database for about 6 months, trying to find credible insights and opportunities for revenue growth.

Database: Sample.db (SQLite Database)

This code assumes that you have converted the three tables to csv files and you have them in the same directory as this notebook file; These steps were done in order to convert these tables to csv;

sqlite> .header on

sqlite> .mode csv

sqlite> .output table-name.csv

sqlite> SELECT * table-name;

So I converted the Products, Transactions and Segments table to csv files.

Utilized Jupyter notebook for the analysis.
