# ETL: Extract, Transform, Load
A classwork example performing ETL skills on a large dataset. Python was used to extract and transform, SQL is used to load and query the data. 

# Overview
In this classwork example SQL queries were performed on behalf of "Independent Funding - a crowdfunding platform for funding independent projects or ventures." They requested a data migration from Excel data files into a PostgreSQL database. After migration, the analytics team will perform further analysis as assigned. This will include reports for company stakeholders and individuals who donate to projects. 

# Summary
Using Python, Pandas, Jupyter Notebook, and a PostgreSQL database:

* Extracted and transformed data from a large Excel file into smaller CSV files
* Created a PostgreSQL database and tables by using an ERD 
* Loaded CSV files into a database
* Ran queries to retrieve data and generate reports for stakeholders

## Images 
First, I used Python to take data from a "dirty" csv file in order to turn it into a "clean" dataframe/ csv file.
### The data before:
![ETL before image](/Queries/data_before.png)

### The data after:
![ETL after image](/Queries/data_after.png)

Next, I planned the connections between the csv data files to prepare before loading the data into SQL:
![DB mapping image](/ERD%20Images/crowdfunding_db_relationships.png)

Finally, a few queries were performed:
![Crowdfunding query](/Queries/crowdfunding_query.png)

*This is fake data for a classwork example*
