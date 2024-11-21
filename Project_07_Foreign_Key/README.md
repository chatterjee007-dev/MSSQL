# Analyzing Company Structure with Hierarchical Data

## Project Overview  
This project focuses on SQL data management to analyze the hierarchical structure of companies. The goal is to count the number of lead managers, senior managers, managers, and employees for each company and retrieve these details along with the company information.

## Key Features  
- **Table Creation**: Define and create multiple tables (`company`, `lead_manager`, `senior_manager`, `manager`, `employee`) with relevant columns and foreign key relationships.
- **Data Insertion**: Insert sample data into each table to simulate a company's hierarchical structure.
- **Data Retrieval**: Write and execute queries to count the number of managers and employees for each company.
- **Hierarchical Querying**: Use subqueries to aggregate data from multiple tables and present a comprehensive view of the company's structure.

## Libraries Used  
- **MSSQL**: The core SQL database management system used for creating and querying the database.

## Code Explanation  
The project includes multiple steps to modularize the implementation:
1. **Creating the `company` table**: Define a table with columns for company code and founder.
2. **Creating the `lead_manager` table**: Define a table with columns for lead manager code and company code, with a foreign key relationship to the `company` table.
3. **Creating the `senior_manager` table**: Define a table with columns for senior manager code, lead manager code, and company code, with foreign key relationships to the `lead_manager` and `company` tables.
4. **Creating the `manager` table**: Define a table with columns for manager code, senior manager code, lead manager code, and company code, with foreign key relationships to the `senior_manager`, `lead_manager`, and `company` tables.
5. **Creating the `employee` table**: Define a table with columns for employee code, manager code, senior manager code, lead manager code, and company code, with foreign key relationships to the `manager`, `senior_manager`, `lead_manager`, and `company` tables.
6. **Inserting Data**: Add sample data into each table to establish a hierarchical structure.
7. **Querying Company Details and Counts**: Write a query to retrieve company details along with the total count of lead managers, senior managers, managers, and employees for each company using subqueries.

## Code Structure  
The code is structured to ensure clarity, reusability, and maintainability:
1. **Creating the `company` table**
2. **Creating the `lead_manager` table**
3. **Creating the `senior_manager` table**
4. **Creating the `manager` table**
5. **Creating the `employee` table**
6. **Inserting data into each table**
7. **Querying company details and counts**

## Prerequisites  
- MSSQL installed on your machine.

## Explanation  
This project demonstrates how to effectively create and manipulate an SQL database with multiple related tables. By writing and executing precise SQL queries, we can analyze the hierarchical structure of a company and retrieve meaningful insights. This showcases essential SQL skills that are valuable in any data-driven role.

## Insights  
- **Table Creation**: Showcased the ability to define multiple related tables with foreign key relationships.
- **Data Insertion**: Demonstrated proficiency in inserting hierarchical data.
- **Hierarchical Querying**: Highlighted the use of subqueries to aggregate data from related tables and present a comprehensive view.
- **Data Analysis**: Illustrated the process of analyzing company structure through SQL.

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
