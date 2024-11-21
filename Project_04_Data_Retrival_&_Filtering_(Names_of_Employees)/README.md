# Retrieving Employee Names by Department Count

## Project Overview  
This project focuses on SQL data retrieval and filtering to identify employees who have worked in at least three different departments. The goal is to demonstrate proficiency in SQL table creation, data manipulation, and complex query writing.

## Key Features  
- **Table Creation**: Define and create an `employee` table with relevant columns.
- **Data Insertion**: Insert multiple rows of data into the table, including scenarios where employees have shifted departments.
- **Data Retrieval**: Write and execute queries to retrieve names of employees who have worked in at least three different departments.
- **Filtering**: Use SQL aggregate functions and subqueries to filter and count distinct departments.

## Libraries Used  
- **MSSQL**: The core SQL database management system used for creating and querying the database.

## Code Explanation  
The project includes multiple steps to modularize the implementation:
1. **Creating the `employee` table**: This step involves defining a table with columns for employee ID, name, department, and salary. Each column is assigned an appropriate data type to ensure data integrity.
2. **Inserting Data**: In this step, multiple rows of data are inserted into the `employee` table, representing various employees, their departments, and salaries. Additional data entries simulate employees shifting departments.
3. **Querying Employees by Department Count**: The main focus here is to write a query that retrieves names of employees who have worked in at least three different departments. This involves using a subquery to count distinct departments for each employee and filtering results where the count is three or more.

## Code Structure  
The code is structured to ensure clarity, reusability, and maintainability:
1. **Creating the `employee` table**
2. **Inserting data into the table**
3. **Querying employees by department count**

## Prerequisites  
- MSSQL installed on your machine.

## Explanation  
This project demonstrates how to effectively create and manipulate an SQL database table. By writing and executing precise SQL queries, we can derive meaningful insights, such as identifying employees who have worked in multiple departments. This showcases essential SQL skills that are valuable in any data-driven role.

## Insights  
- **Table Creation**: Showcased the ability to define structured tables with appropriate data types.
- **Data Manipulation**: Demonstrated proficiency in inserting and querying data.
- **Filtering and Aggregation**: Highlighted the use of aggregate functions and subqueries to count and filter data based on specific criteria.

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
