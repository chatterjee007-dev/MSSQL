# Converting an ER Diagram to Relational Tables

## Project Overview  
This project demonstrates the conversion of an Entity-Relationship (ER) diagram into relational tables in SQL Server. The goal is to ensure a well-structured database capable of handling complex queries efficiently.

## Key Features  
- **Table Creation**: Define and create multiple tables (`Customer`, `Account`, `Branch`, `Loan`, `Depositor`, `Borrower`, `AccountBranch`, `LoanBranch`) with relevant columns and primary key relationships.
- **Relationship Management**: Establish foreign key relationships between tables to reflect the ER diagram accurately.
- **Data Integrity**: Ensure data integrity and consistency through the use of primary and foreign keys.

## Libraries Used  
- **MSSQL**: The core SQL database management system used for creating and querying the database.

## Code Explanation  
The project includes multiple steps to modularize the implementation:
1. **Creating the `Customer` table**: Define a table with columns for customer name, city, and street, with the customer name as the primary key.
2. **Creating the `Account` table**: Define a table with columns for account number and balance, with the account number as the primary key.
3. **Creating the `Branch` table**: Define a table with columns for branch name, city, and assets, with the branch name as the primary key.
4. **Creating the `Loan` table**: Define a table with columns for loan number and amount, with the loan number as the primary key.
5. **Creating the `Depositor` table**: Define a relationship table with columns for customer name and account number, establishing foreign key relationships with the `Customer` and `Account` tables.
6. **Creating the `Borrower` table**: Define a relationship table with columns for customer name and loan number, establishing foreign key relationships with the `Customer` and `Loan` tables.
7. **Creating the `AccountBranch` table**: Define a relationship table with columns for account number and branch name, establishing foreign key relationships with the `Account` and `Branch` tables.
8. **Creating the `LoanBranch` table**: Define a relationship table with columns for loan number and branch name, establishing foreign key relationships with the `Loan` and `Branch` tables.

## Code Structure  
The code is structured to ensure clarity, reusability, and maintainability:
1. **Creating the `Customer` table**
2. **Creating the `Account` table**
3. **Creating the `Branch` table**
4. **Creating the `Loan` table**
5. **Creating the `Depositor` table**
6. **Creating the `Borrower` table**
7. **Creating the `AccountBranch` table**
8. **Creating the `LoanBranch` table**

## Prerequisites  
- MSSQL installed on your machine.

## Explanation  
This project demonstrates how to effectively convert an ER diagram into relational tables in SQL Server. By following these steps, we ensure our database is well-structured and capable of handling complex queries efficiently. This showcases essential SQL skills that are valuable in any data-driven role.

## Insights  
- **Table Creation**: Showcased the ability to define multiple related tables with primary and foreign key relationships.
- **Relationship Management**: Demonstrated proficiency in establishing foreign key relationships to maintain data integrity.
- **Data Integrity**: Highlighted the use of primary and foreign keys to ensure data consistency and reliability.
- **Database Design**: Illustrated the process of converting an ER diagram into a well-structured relational database.

## Future Enhancements

1. **Advanced Querying**:
   - Implement more complex queries involving joins, subqueries, and window functions.

2. **Data Integrity**:
   - Add additional constraints and indexes to further enhance data integrity and query performance.

3. **Normalization**:
   - Normalize the database to eliminate redundancy and improve data organization.

4. **Stored Procedures and Functions**:
   - Create stored procedures and functions to encapsulate complex business logic.

5. **Performance Tuning**:
   - Optimize queries and database schema for better performance.
