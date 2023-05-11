# SQL_Covid19_DataAnalysis

In this SQL Project, the dataset is extracted from kaggle and then split into two tables - Deaths and Vaccinations using Excel. I have done an exploratory analysis using basic to advanced queries.

Steps Included:
* Download Raw Data: Downloaded the raw data related to COVID-19 deaths and vaccination from Kaggle. 
* Split Data into Tables: Used the Microsfot Excel to split the downloaded data into two separate tables - one for Deaths and another for Vaccination. 
* Create Tables: Used the csvkit library to create the tables using the excel files. This python library will automatically create the tables with appropriate column names, data types, and any necessary constraints based on the structure and contents of the excel files.
* Load Data into Snowflake: Loaded the data from the split CSV files into the corresponding tables in Snowflake.
* Perform SQL Queries: Wrote SQL queries in Snowflake to perform the desired analysis on the COVID-19 deaths and vaccination data. You can use Snowflake's SQL capabilities to aggregate, filter, join, or perform any other necessary operations to derive insights from the data.
* Analyze the Data: Executed the SQL queries to retrieve the desired information and analyze the data. You can calculate death percentages, vaccination rates, trends over time, compare different regions, and perform any other relevant analysis based on the available data.

The raw dataset was downloaded from https://ourworldindata.org/covid-deaths






