# SQLAlchemy

Go through the SQLAlchemy tutorial
[https://docs.sqlalchemy.org/en/13/orm/tutorial.html](https://docs.sqlalchemy.org/en/13/orm/tutorial.html)

## Data Project, SQLAlchemy version

*NOTE:* the database for this project should be PostgreSQL.

### Part 1. SQL scripts to create, drop database
Create "helper" SQL scripts that makes it easy to run your code.

1. Script 1, create script - should create a new database on which the SQLAlchemy code will run.
2. Script 2, delete script - should drop the database of this project. To help clean up after running your code.

### Part 2. SQLAlchemy loader script
This script should load the **entire** csv data from your previous data projects into the data base.

#### TASKS
1. Design table schema, based on your csv.
2. *Note* that you might have multiple tables. Either for multiple csv or supporting data like country lists / state lists etc. You must design Primary Key - Foreign Key relations for those.
3. Write SQLAlchemy code for ...
    * mapping declarations
    * creating schema
    * write SQLalchemy code to generate JSON files similar **JS data project** but this use your database instead of csv file.

### Part 3
Copy the html / js code from the previous project and test against the json generated in *Part 2*
