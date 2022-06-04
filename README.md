# DATA 514 System Investigation Project<br>
Madalyn Li<br>
Spring 2022

# Background
The purpose of this project is to allow us to explore and gain experience with a data management system of our choice. For the last part of the project, we were tasked with selecting a dataset and a handful of queries to answer using the data management system we chose. For this part of the project, I have opted to explore the Airbnb dataset and answer three selected queries that were provided with the dataset using Apache Spark. The three queries are listed as follows:

1.	Display list of stays in Portland, OR with details: name, neighbourhood, room type, how many guests it accommodates, property type and amenities, per night’s cost and is available for the next two days in descending order of rating.
2.	Are there any neighbourhoods in any of the cities that don’t have any listings?
3.	For each city, how many reviews are received for December of each year?

This repository details the code used to clean the original data from the source, create Dataframes with the Data using Spark, and running the queries within Spark. 

# Data

The data for this project Is derived from the source [Inside Airbnb](http://insideairbnb.com/get-the-data/) which contains files of data for Airbnb listings, calendar bookings, reviews, and neighborhoods of various cities and countries. For this project, we were asked to focus on the following cities in the US: Los Angeles, Portland, Salem, and San Diego.

# File Description

Below is a table of the descriptions for each file within this repository. They are listed in the order to follow along to reproduce the query results:

| File Name | Description |
| --- | --- |
| **clean_airbnb_data.ipynb** | File containing code to clean and prepare original data for analysis |
| **cleaned_airbnb_data.zip** | Zip file containing all of the finalized and cleaned data for analysis |
| **create_airbnb_dataframes.ipynb** | File containing code to create dataframes using the data with Spark  |
| **airbnb_queries.ipnyb** | File containing code to run queries using dataframes in Spark |
| **query1.csv** | CSV file for the results of query 1 |
| **query2_LA.csv** | CSV file for the results of query 2 for Los Angeles |
| **query2_Portland.csv** | CSV file for the results of query 2 for Portland |
| **query2_Salem.csv** | CSV file for the results of query 2 for Salem |
| **query2_SD.csv** | CSV file for the results of query 2 for San Diego |
| **query3_LA.csv** | CSV file for the results of query 3 for Los Angeles |
| **query3_Portland.csv** | CSV file for the results of query 3 for Portland |
| **query3_Salem.csv** | CSV file for the results of query 3 for Salem |
| **query3_SD.csv** | CSV file for the results of query 3 for San Diego |



