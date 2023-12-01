# Crowdfunding_ETL
UC Berkeley Extension Data Analysis Project 2 ETL Challenge

This ETL mini project challenge includes building an ETL pipeline using `Python`, `Pandas`, and either Python dictionary methods or regular expressions to extract and transform the data. 

After transforming the data, four CSV files will be created, this will be the basis of the project's `Postgres` database. From the said CSV files data, an ERD and a table schema were created to illustrate the table relationship. To finish the ETL project, the data from the derived CSV files will be imported into a Postgres database.

### Summary

Using Python, Pandas, Jupyter Notebook, and a PostgreSQL database:

- Extracted and transformed data from an Excel spreadsheet into smaller CSV files

- Created a PostgreSQL database and tables by using an ERD

- Loaded CSV files into a database

- Ran queries to retrieve data and generate reports for stakeholders

### List of deliverables

1. [ETL Mini Project Jupyter Notebook](https://github.com/rabellan/Crowdfunding_ETL/blob/main/ETL_Mini_Project_RAbellano.ipynb) - Jupyter Notebook for creating the `category`, `subcategory`, `campaign`, and `contacts` DataFrames.

2. [Campaign ERD Diagram](https://github.com/rabellan/Crowdfunding_ETL/blob/main/Resources/campaign_ERD.png)

3. [crowdfunding_db_schema.sql](https://github.com/rabellan/Crowdfunding_ETL/blob/main/Resources/SQL/crowdfunding_db_schema.sql) - the SQL schema that built 'crowdfunding_db' in Postgres DB

4. [crowdfunding_db.sql](https://github.com/rabellan/Crowdfunding_ETL/blob/main/Resources/SQL/crowdfunding_db.sql) - the SQL used to verify the successful importation of CSV files into the proper tables in `crowdfunding_db`

### Resources folder

#### Excel files from the project "starter kit"

1. [crowdfunding.xlsx](https://github.com/rabellan/Crowdfunding_ETL/blob/main/Resources/RAW/crowdfunding.xlsx) - Excel spreadsheet source of the crowdfunding DataFrame exercise

2. [contacts.xslx](https://github.com/rabellan/Crowdfunding_ETL/blob/main/Resources/RAW/contacts.xlsx) - Excel spreadsheet source for the contacts DataFrame exercise

#### CSV results files from the DataFrames exercises of the Crowdfunding ETL project 

1. [category.csv](https://github.com/rabellan/Crowdfunding_ETL/blob/main/Resources/CSV/category.csv) - Exported categories_df as CSV file. A screenshot of the successful SQL query of the category table can be found [here](https://github.com/rabellan/Crowdfunding_ETL/blob/main/Resources/Images/category_sql.png)

2. [subcategory.csv](https://github.com/rabellan/Crowdfunding_ETL/blob/main/Resources/CSV/subcategory.csv) - Exported subcategories_df as CSV file. A screenshot of the successful SQL query of the subcategory table can be found [here](https://github.com/rabellan/Crowdfunding_ETL/blob/main/Resources/Images/subcategory_sql.png)

3. [contacts.csv](https://github.com/rabellan/Crowdfunding_ETL/blob/main/Resources/CSV/contacts.csv) - Exported 'contacts.csv' from the 'Create Contacts DataFrame" exercise. A screenshot of the successful SQL query of the contacts table can be found [here](https://github.com/rabellan/Crowdfunding_ETL/blob/main/Resources/Images/contacts_sql.png)

4. [campaign.csv](https://github.com/rabellan/Crowdfunding_ETL/blob/main/Resources/CSV/campaign.csv) - Exported 'campaign.csv' from the exported campaign DataFrame. A screenshot of the successful SQL query of the campaign table can be found [here](https://github.com/rabellan/Crowdfunding_ETL/blob/main/Resources/Images/campaign_sql.png)

Here is the screenshot of the successful importation of the results CSV files:

![Postgres Import](https://github.com/rabellan/Crowdfunding_ETL/blob/main/Resources/Images/CSV_Import.png)

---

### Entity Relationship Diagram

![ERD Diagram - Crowdfunding](https://github.com/rabellan/Crowdfunding_ETL/blob/main/Resources/Images/campaign_ERD.png)