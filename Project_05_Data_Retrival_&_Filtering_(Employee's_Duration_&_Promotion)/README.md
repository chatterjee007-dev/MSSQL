# Analyzing Employee Data for Promotions Using Data Retrieval and Filtering

## Project Overview  
This project focuses on SQL data retrieval and manipulation to identify employees eligible for promotions. The goal is to demonstrate proficiency in SQL table creation, data manipulation, and complex query writing.

## Key Features  
- **Table Creation**: Define and create an `employee` table with relevant columns.
- **Data Insertion**: Insert multiple rows of data into the table, including scenarios where employees have shifted departments.
- **Data Retrieval**: Write and execute queries to identify employees who have worked for more than three years and those who have not received a salary increment despite working in the company for over three years.
- **Data Transformation**: Use SQL to add new columns and update existing data based on specific conditions.

## Libraries Used  
- **MSSQL**: The core SQL database management system used for creating and querying the database.

## Code Explanation  
The project includes multiple steps to modularize the implementation:
1. **Creating the `employee` table**: This step involves defining a table with columns for employee ID, name, department, and salary. Each column is assigned an appropriate data type to ensure data integrity.
2. **Inserting Data**: In this step, multiple rows of data are inserted into the `employee` table, representing various employees, their departments, and salaries. Additional data entries simulate employees shifting departments.
3. **Altering the Table**: This step involves adding a new column `duration` to the table to track the number of years an employee has been with the company.
4. **Updating Data**: In this step, the `duration` column is updated based on specific conditions to reflect how long each employee has been with the company.
5. **Querying Employees for Promotions**: The main focus here is to write queries that identify employees who have worked for more than three years and those who have not received a salary increment despite being with the company for over three years. This involves using a common table expression (CTE) and the LAG window function to compare current and previous department values.

## Code Structure  
The code is structured to ensure clarity, reusability, and maintainability:
1. **Creating the `employee` table**
2. **Inserting data into the table**
3. **Altering the table to add the `duration` column**
4. **Updating the `duration` column based on conditions**
5. **Querying employees for promotion eligibility**

## Prerequisites  
- MSSQL installed on your machine.

## Explanation  
This project demonstrates how to effectively create and manipulate an SQL database table. By writing and executing precise SQL queries, we can derive meaningful insights, such as identifying employees who are eligible for promotions. This showcases essential SQL skills that are valuable in any data-driven role.

## Insights  
- **Table Creation**: Showcased the ability to define structured tables with appropriate data types.
- **Data Manipulation**: Demonstrated proficiency in inserting, updating, and querying data.
- **Data Transformation**: Highlighted the use of SQL to transform data by adding and updating columns based on specific conditions.
- **Complex Queries**: Illustrated the use of common table expressions (CTEs) and window functions to perform advanced data analysis.

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

