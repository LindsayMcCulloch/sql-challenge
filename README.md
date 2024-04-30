# sql-challenge
This is the repository for Monash University Data Analytics Bootcamp Module 9 Challenge

# How to use
- Entity Relationship Diagram is included in file Data_Modelling.png
  
- Table schemata for each CSV file can be found in file Data_Engineering.sql
  
- Queries for the table data can be foun in file Data_Analysis.sql
  
- CSV files used are located in "Resources" folder 

Background:
--------------------------------------------------------------------------------------------------------------------------------
It’s been two weeks since you were hired as a new data engineer at Pewlett Hackard (a fictional company). Your first major task is to do a research project about people whom the company employed during the 1980s and 1990s. All that remains of the employee database from that period are six CSV files.

For this project, you’ll design the tables to hold the data from the CSV files, import the CSV files into a SQL database, and then answer questions about the data. That is, you’ll perform data modelling, data engineering, and data analysis, respectively.

Instructions
--------------------------------------------------------------------------------------------------------------------------------

This Challenge is divided into three parts: data modelling, data engineering, and data analysis.

Data Modelling
--------------------------------------------------------------------------------------------------------------------------------

Inspect the CSV files, and then sketch an ERD of the tables. To create the sketch, feel free to use a tool like QuickDBDLinks to an external site..

Data Engineering
--------------------------------------------------------------------------------------------------------------------------------

Use the provided information to create a table schema for each of the six CSV files. Be sure to do the following:

Remember to specify the data types, primary keys, foreign keys, and other constraints.

For the primary keys, verify that the column is unique. Otherwise, create a composite keyLinks to an external site., which takes two primary keys to uniquely identify a row.

Be sure to create the tables in the correct order to handle the foreign keys.

Import each CSV file into its corresponding SQL table.

Data Analysis
--------------------------------------------------------------------------------------------------------------------------------

List the employee number, last name, first name, sex, and salary of each employee.

List the first name, last name, and hire date for the employees who were hired in 1986.

List the manager of each department along with their department number, department name, employee number, last name, and first name.

List the department number for each employee along with that employee’s employee number, last name, first name, and department name.

List the first name, last name, and sex of each employee whose first name is Hercules and whose last name begins with the letter B.

List each employee in the Sales department, including their employee number, last name, and first name.

List each employee in the Sales and Development departments, including their employee number, last name, first name, and department name.

List the frequency counts, in descending order, of all the employee last names (that is, how many employees share each last name).

Resources used:
--------------------------------------------------------------------------------------------------------------------------------
BCS Xpert Learning assistant 

Office Hours

https://stackoverflow.com/questions/3474389/how-to-visualize-the-relationships-between-tables-of-a-database-schema

https://www.pgadmin.org/docs/pgadmin4/latest/erd_tool.html

https://medium.com/geekculture/creating-a-sql-entity-relationship-diagram-erd-ced5ad1239d0

https://www.postgresql.org/message-id/23d251df0906252312i33fe2cb8ue74ee0a19a64518a@mail.gmail.com

https://dba.stackexchange.com/questions/169202/failed-import-of-date-using-copy

https://stackoverflow.com/questions/68337925/i-am-unable-to-upload-a-csv-file-in-postgresql-database-because-i-dont-know-ho

https://stackoverflow.com/questions/13244460/how-to-change-datestyle-in-postgresql

https://stackoverflow.com/questions/48722878/date-in-table-is-dd-mm-yyyy-cant-import-to-postgres-via-csv
