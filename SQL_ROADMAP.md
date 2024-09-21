## SQL Learning Roadmap & Syllabus

### Introduction to Databases

1. What is a Database?
2. Definition, purpose, types (SQL vs NoSQL)
3. Database Models
4. Relational databases (RDBMS)
5. Non-relational databases (NoSQL: Document, Key-Value, Graph, Column-family)
6. Popular Database Systems
   SQL: MySQL, PostgreSQL, Oracle, MS SQL Server
   NoSQL: MongoDB, Cassandra, Redis
7. SQL vs NoSQL

### SQL Databases

1. Structured, uses schema, relational models, tables with rows and columns
2. NoSQL Databases
3. Flexible schema, handles unstructured data (e.g., JSON, XML)
4. Use cases: scalability, big data, real-time applications
5. When to use SQL vs NoSQL?
6. Introduction to SQL
7. What is SQL?
8. Definition, structure, and use cases
9. SQL Syntax
10. Case sensitivity, standard SQL syntax structure
11. SQL Tools
12. SQL command line, GUI tools (MySQL Workbench, pgAdmin, DBeaver)
    SQL Sub-Languages

### DDL (Data Definition Language)

`CREATE, ALTER, DROP, TRUNCATE, RENAME`

### DML (Data Manipulation Language)

`INSERT, UPDATE, DELETE, MERGE`

### DQL (Data Query Language)

`SELECT Using WHERE, ORDER BY, GROUP BY, HAVING`

### TCL (Transaction Control Language)

`COMMIT, ROLLBACK, SAVEPOINT`

### ACID Properties

1. Atomicity
   Ensuring all tasks in a transaction are completed or none
2. Consistency
   Data must be in a valid state after a transaction
3. Isolation
   Transactions must be isolated from each other
4. Durability
   Once a transaction is committed, changes are permanent

### Basic SQL Queries

1. SELECT and FROM
2. Filtering data using WHERE
3. Sorting data with ORDER BY
4. Aggregate functions (COUNT, SUM, AVG, MIN, MAX)
5. Grouping data with GROUP BY and filtering grouped data using HAVING
6. Intermediate SQL Queries
7. Joins (INNER JOIN, LEFT JOIN, RIGHT JOIN, FULL OUTER JOIN)
8. Subqueries (Nested queries)
9. Set operations (UNION, INTERSECT, EXCEPT)
10. DISTINCT for removing duplicates
11. Advanced SQL Queries
12. Window Functions (ROW_NUMBER(), RANK(), LEAD(), LAG())
13. Common Table Expressions (CTE)
14. Recursive Queries
15. Working with JSON/XML data in SQL
16. Writing optimized queries
17. Handling NULLs in queries
18. Using indexes for performance
19. Database Design and Normalization

### Normalization

1. 1NF, 2NF, 3NF, BCNF
2. Denormalization
3. ER Diagrams
4. Entity-relationship modeling
5. Primary Key, Foreign Key, and Indexes
6. Importance and use cases
7. Data Integrity and Constraints
8. NOT NULL, UNIQUE, CHECK, DEFAULT, FOREIGN KEY
9. Transactions and Concurrency Control

### Projects and Exercises

1. Building a small relational database for a simple app (e.g., e-commerce, inventory management)
2. Mini Projects
   - Create a blog database schema with authors, posts, comments, and tags
   - Create a student management system with courses, students, grades, and attendance
   - Capstone Project
     Design, develop, and optimize a complete database for an enterprise-level system (HR, finance, inventory, etc.)
