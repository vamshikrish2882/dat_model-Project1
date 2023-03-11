# Data_modeling 

Data Modeling  is the process of simplifying the diagram or data model of a software system by applying certain formal techniques. It involves expressing data and information through text and symbols. The data model provides the blueprint for building a new database or reengineering legacy applications.
#### Data modeling is necessary foundational work. It allows data to be easily stored in a database and positively impacts data analytics. It is critical for data management, data governance, and data intelligence. 

It means better documentation of data sources, higher quality and clearer scope of data use with faster performance and few errors.

From the regulatory compliance view, data modeling ensures that an organization adheres to governmental laws and applicable industry regulations.

It empowers employees to make data-driven decisions and strategies.

It builds on business intelligence as it allows the identification of new opportunities by expanding data capability.

## Psycopg2

In this project, I have created a database and built tables in dtabase using psycopg2 library in python.

Firstly installed psycopg2 and pandas packages on to the jupyter notebook.Then connected to the localhost and exisiting postgres database using sql shell terminal.
Created a new database "formula1" using this connection and cursor fumctions from Psycopg2 package. Now after creating the new database "formula1" I have closed the existing connection and stargted new connection with the newly created database.
## Data Cleaning:

I have taken a formula1 dataset from kaggle, then cleaned and transformed csv data into a DataFrame using pandas library.

## Data Model:

After cleaning the data I have built a relational data model of three tables using Draw.io

![data model](https://user-images.githubusercontent.com/122099372/224493776-1a8220af-19d7-49aa-8542-a29104c39c6d.png)

## Create Tables and Insert Data:

i have created tables for csv data files respectively using standard sql query for creating tables as planned in the data model.
Then inserted the values into the created tables with for loop.

## PostgeSQL:

I used PostgreSql for querying the created new database "formula1".

## Datasets:

I have created three new tables on to the new data base "formula1" using the csv data files
1. Drivers table using GrandPrix_drivers_details_1950_to_2022 file
2. Laps table using GrandPrix_fastest_laps_details_1950_to_2022 file
3. Records table using GrandPrix_races_details_1950_to_2022 file
 
link: https://www.kaggle.com/datasets/tusharsingh1411/formula1-data-1950-2022




