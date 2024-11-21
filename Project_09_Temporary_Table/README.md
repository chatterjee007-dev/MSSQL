# Managing Data with Local and Global Temporary Tables

## Project Overview  
This project demonstrates the creation, usage, and deletion of both local and global temporary tables in SQL Server. The goal is to showcase the ability to manage intermediate data efficiently within a session using temporary tables.

## Key Features  
- **Local Temporary Tables**: Create and manage local temporary tables, which are specific to the session in which they are created.
- **Global Temporary Tables**: Create and manage global temporary tables, which are accessible across multiple sessions.
- **Data Insertion and Verification**: Insert sample data into temporary tables and verify the inserted values.
- **Table Deletion**: Demonstrate the deletion of both local and global temporary tables.

## Libraries Used  
- **MSSQL**: The core SQL database management system used for creating and querying the database.

## Code Explanation  
The project includes multiple steps to modularize the implementation:
1. **Creating a Local Temporary Table**: Define a table with columns for employee ID, name, and salary. This table is specific to the session in which it is created, using the `#` prefix.
2. **Inserting Values into the Local Temporary Table**: Insert sample data into the local temporary table to simulate employee records.
3. **Creating a Global Temporary Table**: Define a table with columns for employee ID, name, and salary. This table is accessible across multiple sessions, using the `##` prefix.
4. **Inserting Values into the Global Temporary Table**: Insert sample data into the global temporary table to simulate employee records.
5. **Deleting the Local Temporary Table**: Demonstrate the deletion of the local temporary table, which is automatically dropped when the session ends but can be explicitly dropped if needed.
6. **Deleting the Global Temporary Table**: Demonstrate the deletion of the global temporary table, which can be explicitly dropped.

## Code Structure  
The code is structured to ensure clarity, reusability, and maintainability:
1. **Creating the Local Temporary Table**
2. **Inserting values into the Local Temporary Table**
3. **Creating the Global Temporary Table**
4. **Inserting values into the Global Temporary Table**
5. **Deleting the Local Temporary Table**
6. **Deleting the Global Temporary Table**

## Prerequisites  
- MSSQL installed on your machine.

## Explanation  
This project demonstrates how to effectively create and manipulate local and global temporary tables in SQL Server. By writing and executing precise SQL queries, we can manage intermediate data efficiently within a session. This showcases essential SQL skills that are valuable in any data-driven role.

## Insights  
- **Temporary Table Creation**: Showcased the ability to define both local and global temporary tables.
- **Data Insertion and Verification**: Demonstrated proficiency in inserting and verifying data in temporary tables.
- **Table Deletion**: Highlighted the process of deleting both local and global temporary tables.
- **Data Management**: Illustrated the use of temporary tables for efficient data manipulation and processing.

## Future Enhancements

1. **Advanced Querying**:
   - Implement more complex queries involving temporary tables and their interactions with permanent tables.

2. **Data Integrity**:
   - Add constraints to temporary tables to ensure data integrity during processing.

3. **Normalization**:
   - Use temporary tables in conjunction with normalized databases for better data organization.

4. **Stored Procedures and Functions**:
   - Create stored procedures and functions that utilize temporary tables for complex data processing tasks.

5. **Performance Tuning**:
   - Optimize the use of temporary tables to enhance query performance and efficiency.
