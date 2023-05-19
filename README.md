# Crowdfunding_ETL
ETL mini project

Project 2 ,Group 8: Ava Tahmasebi and Rana Mousavi
Note: We worked through all of the project together but created our own individual Jupyter notebook and repos.
In this collaborative ETL (Extract, Transform, Load) mini project, our team utilized Python, Pandas, and data manipulation techniques to build an efficient data pipeline. We extracted data from various sources, transformed it, and loaded it into a PostgreSQL database.

Our project involved creating the category and subcategory DataFrames by extracting and transforming data from the crowdfunding.xlsx file. We then exported them as category.csv and subcategory.csv files. Additionally, we processed the campaign DataFrame by converting data types, renaming columns, and adjusting datetime formats. The resulting campaign.csv file contained essential information about campaigns.

Furthermore, we utilized Python dictionary methods to extract and transform data from the contacts.xlsx file. We split names into first and last names, resulting in the creation of the contacts.csv file.

To ensure data integrity, we designed a well-structured database schema based on the provided ERD. The crowdfunding_db_schema.sql file contained table schemas, data types, primary and foreign keys, and constraints. We created the crowdfunding_db database and successfully loaded the data using the schema.
