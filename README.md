# Basics-of-SQL

# SQL- Structured Query Language

## A brief and yet detailed knowlege of SQL-Structured Query language.

SQL (Structured Query Language) is a powerful language used for managing and manipulating relational databases. It enables users to retrieve, insert, update, and delete data efficiently, ensuring structured and consistent data storage while supporting complex queries for data analysis and reporting.

## SQL Process
- SQL Query
- Query Language Operator
- DBMS Engine
- Physical Database
- Parser+ Optimiser
- File manager + Transaction manager

## Types Of RDMBS
  -My SQL
  -Postgresql
  -SQL server

## Some SQL Commands
  Here are some common SQL commands:

1. **SELECT**: Retrieves data from a database.
   ```sql
   SELECT * FROM users;
   ```

2. **INSERT**: Adds new records to a table.
   ```sql
   INSERT INTO users (name, age) VALUES ('Alice', 30);
   ```

3. **UPDATE**: Modifies existing data in a table.
   ```sql
   UPDATE users SET age = 31 WHERE name = 'Alice';
   ```

4. **DELETE**: Removes records from a table.
   ```sql
   DELETE FROM users WHERE name = 'Alice';
   ```

5. **CREATE TABLE**: Creates a new table.
   ```sql
   CREATE TABLE users (id INT, name VARCHAR(50), age INT);
   ```
## How Tables can be created

```
CREATE TABLE Students (
  StudentID INT PRIMARY KEY,
  FirstName VARCHAR(50) NOT NULL,
  LastName VARCHAR(50) NOT NULL,
  Email VARCHAR(100) UNIQUE,
  DateOfBirth DATE,
  Gender VARCHAR(10),
  Course VARCHAR(50),
  Department VARCHAR(50),
  CreatedAt TIMESTAMP DEFAULT CURRENT_TIMESTAMP);
```
## Tpes Of Commands in SQL

SQL commands can be categorized into five main types based on their functionality:

### 1. **DQL (Data Query Language)**  
   Used to query and retrieve data from the database.

### 2. **DML (Data Manipulation Language)**  
   Used to modify the data in the database.
   
### 3. **DDL (Data Definition Language)**  
   Used to define and manage database structure, such as tables, views, and schemas.

### 4. **DCL (Data Control Language)**  
   Used to control access to data in the database.

  

