# Crowdfunding-ETL

## Overview
Independent Funding is a crowdfunding platform for funding independent projects or ventures.

Independent Funding has been growing, so now it needs to move all their accessible data from one large Excel file onto a PostgreSQL database. This way, the analytics team will be able to perform analysis and create reports for company stakeholders as well as individuals who donate to projects.

We were tasked with the following:
* Extracting and transforming the data from large Excel files into five separate CSV files: contacts.csv, campaign.csv, category.csv, subcategory.csv, backers.csv
* Creating a PostgreSQL database and tables by using an ERD: crowdfunding_db_relationships.png, crowdfunding_db_schema.sql
* Loading the CSV files into the database
* Perform data analysis on the crowdfunding_db database using SQL: crowdfunding_SQL_Analysis.sql

In the Challenge, we used Python, Pandas, and Jupyter notebooks to do the extract and transform phases. And we used PostgreSQL and pgAdmin 4 for the SQL analysis.

*Source: Bootcamp Spot Challenge 8 Instructions.*

