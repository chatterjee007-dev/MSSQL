# Querying City Names Without Vowels

## Project Overview  
This project involves creating an SQL table to store city information and querying the table to retrieve city names that do not end with vowels. The objective is to demonstrate proficiency in SQL table creation, data insertion, and data retrieval using pattern matching.

## Key Features  
- **Table Creation**: Define and create a `cities` table with relevant columns.
- **Data Insertion**: Insert multiple rows of data into the table.
- **Data Retrieval**: Write and execute queries to retrieve city names that do not end with vowels.
- **Pattern Matching**: Use SQL LIKE operator to filter results based on pattern matching.

## Libraries Used  
- **MSSQL**: The core SQL database management system used for creating and querying the database.

## Code Explanation  
The project includes multiple steps to modularize the implementation:
1. **Creating the `cities` table**: This step involves defining a table with columns for city ID, name, and state. Each column is assigned an appropriate data type to ensure data integrity.
2. **Inserting Data**: In this step, multiple rows of data are inserted into the `cities` table, representing various cities and their states. This step demonstrates how to populate a table with initial data entries.
3. **Querying City Names Without Vowels**: The main focus here is to write a query that retrieves city names that do not end with vowels. This involves using the SQL LIKE operator with a pattern that excludes vowels.

## Code Structure  
The code is structured to ensure clarity, reusability, and maintainability:
1. **Creating the `cities` table**
2. **Inserting data into the table**
3. **Querying city names without vowels**

## Prerequisites  
- MSSQL installed on your machine.

## Explanation  
This project demonstrates how to effectively create and manipulate an SQL database table. By writing and executing precise SQL queries, we can derive meaningful insights, such as identifying city names that do not end with vowels. This showcases essential SQL skills that are valuable in any data-driven role.

## Insights  
- **Table Creation**: Showcased the ability to define structured tables with appropriate data types.
- **Data Manipulation**: Demonstrated proficiency in inserting and querying data.
- **Pattern Matching**: Highlighted the use of the SQL LIKE operator to filter results based on patterns.

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
