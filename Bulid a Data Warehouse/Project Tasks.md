# Exercise 1 - Design a Data Warehouse

You will start your project by designing a Star Schema for the warehouse by identifying the columns for the various dimension and fact tables in the schema. Name your database as softcart

### Task 1 - Design the dimension table softcartDimDate
Using the ERD design tool design the table softcartDimDate. The company is looking at a granularity of a day. Which means they would like to have the ability to generate the report on yearly, monthly, daily, and weekday basis.

Here is a partial list of fields to serve as an example:

dateid

month

monthname

…

…

Take a screenshot of the table softcartDimDate in the ERD tool clearly showing all the fieldnames and data types.

*Name the screenshot softcartDimDate*

### Task 2 - Design the dimension table softcartDimCategory
Using the ERD design tool design the table softcartDimCategory.

### Task 3 - Design the dimension table softcartDimItem
Using the ERD design tool design the table softcartDimItem.

### Task 4 - Design the dimension table softcartDimCountry
Using the ERD design tool design the table softcartDimCountry.

Take a screenshot clearly showing all three tables(softcartDimCategory, softcartDimItem, softcartDimCountry) in the ERD tool with all the fieldnames and data types. 

*Name the screenshot dimtables*

### Task 5 - Design the fact table softcartFactSales
Using the ERD design tool design the table softcartFactSales.

Take a screenshot of the table softcartFactSales in the ERD tool clearly showing all the fieldnames and data types.

*Name the screenshot softcartFactSales*

### Task 6 - Design the relationships
Using the ERD design tool design the required relationships(one-to-one, one-to-many etc) amongst the tables.

Take a screenshot of the entire ERD clearly showing all the relationships amongst the tables.

*Name the screenshot softcartRelationships*

------------------------------------------------------------------------------------------------------------------

# Exercise 2 - Create the schema

In this exercise you will create the schema of the data warehouse.

### Task 7 - Create the schema.

Download the schema sql from ERD tool and create the schema in a database named staging.
Take a screenshot showing the success of the schema creation.

*Name the screenshot createschema*

## End of the assignment.
