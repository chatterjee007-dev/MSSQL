# Finding the Second Highest Salary Using Aggregate Function

## Project Overview  
This project focuses on using SQL aggregate functions to find the second highest salary in the "Salary" table without using the LIMIT clause. The goal is to demonstrate proficiency in writing complex SQL queries and manipulating data within a database.

## Key Features  
- **Table Creation**: Define and create an `employee` table with relevant columns.
- **Data Insertion**: Insert multiple rows of data into the table.
- **Data Retrieval**: Write and execute queries to retrieve data and identify the second highest salary.
- **Aggregation**: Use SQL functions to aggregate data and perform calculations.

## Libraries Used  
- **MSSQL**: The core SQL database management system used for creating and querying the database.

## Code Explanation  
The project includes multiple steps to modularize the implementation:
1. **Creating the `employee` table**: This step involves defining a table with columns for employee ID, name, department, and salary. Each column is assigned an appropriate data type to ensure data integrity.
2. **Inserting Data**: In this step, multiple rows of data are inserted into the `employee` table, representing various employees and their salaries. This step demonstrates how to populate a table with initial data entries.
3. **Querying the Second Highest Salary**: The main focus here is to write a query that retrieves the second highest salary without using the LIMIT clause. This involves using a sub-query to find the maximum salary and then another query to find the maximum salary that is less than the maximum obtained from the sub-query.

## Code Structure  
The code is structured to ensure clarity, reusability, and maintainability:
1. **Creating the `employee` table**
2. **Inserting data into the table**
3. **Querying the second highest salary**

## Prerequisites  
- MSSQL installed on your machine.

## Explanation  
This project demonstrates how to effectively create and manipulate an SQL database table. By writing and executing precise SQL queries, we can derive meaningful insights, such as identifying the second highest salary. This showcases essential SQL skills that are valuable in any data-driven role.

## Insights  
- **Table Creation**: Showcased the ability to define structured tables with appropriate data types.
- **Data Manipulation**: Demonstrated proficiency in inserting and querying data.
- **Aggregation**: Highlighted the use of aggregate functions to perform calculations on data.

## Future Enhancements

1. **Advanced Querying**:
   - Implement more complex queries involving joins, subqueries, and window functions.

2. **Data Integrity**:
   - Add constraints and indexes to enhance data integrity and query performance.

3. **Normalization**:
   - Normalize the database to eliminate redundancy and improve data organization.

4. **Stored Procedures and Functions**:
   - Create stored procedures and functions to encapsulate complex business logic.

5. **Performance Tuning**:
   - Optimize queries and database schema for better performance.
