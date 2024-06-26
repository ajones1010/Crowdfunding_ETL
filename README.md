# Crowdfunding_ETL

Team 5: Project 2


Team Members: Savi Rahiman and Alyssa Jones


Project Description/Outline: The aim of our project is to analyze crowdfunding and campaign data to create an ERD table schema in SQL resulting in an ETL pipeline. In the first part of the project, we analyzed data from two excel spreadsheets, contacts.xlsx and crowdfunding.xlsx, and created four CSV files, campaign.csv, contacts.csv, category.csv, and subcategory.csv. After creating the four CSV files, we then created an ERD table schema and verified the data using Postgres SQL. 


Part 1 - Analyzing Crowdfunding Excel Spreedsheet:

Using the crowdfunding.xlsx data, three CSV files were created, labeled campaign.csv, category.csv, and subcategory.csv. Using the dataframes from the csv files, the campaign dataframe was created. The dataframe was cleaned and formatted to execute analysis. 

Part 2 - Analyzing Contacts Excel Spreedsheet:

Using the contacts.xlsx data, the process of regex was used to clean the data and create the contacts.csv.


Part 3 - Creating the Entity Relationship Diagram (ERD):


Using the four csv files created from the previous parts, an ERD was created using https://www.quickdatabasediagrams.com. The ERD was then exported into PostgreSQL.


Part 4 - Creating the SQL Database Schema:

Using the database schema, crowdfunding_db.sql was created, which included the appropriate primary and foreign keys from our ERD. We then created four tables, each containing a csv file, respective to their file name. All four tables were ran and checked clear of errors.
