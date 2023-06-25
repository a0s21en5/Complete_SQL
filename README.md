# SQL and RDBMS

## SQL: Structured Query Language

SQL stands for Structured Query Language and is used to access and manipulate data in relational databases. It is a language that allows users to interact with databases and perform various operations.

### CRUD Operations

SQL uses CRUD operations to communicate with databases. CRUD stands for Create, Read, Update, and Delete, and these operations allow users to manage the data in the database.

1. CREATE: The CREATE operation is used to execute INSERT statements to insert new tuples into a relation.
2. READ: The READ operation is used to read data already present in the relations.
3. UPDATE: The UPDATE operation is used to modify already inserted data in the relation.
4. DELETE: The DELETE operation is used to delete specific data points/tuples/rows or multiple rows.

### SQL vs. RDBMS

It is important to note that SQL is not a database itself but a query language used to interact with databases. An RDBMS (Relational Database Management System) is a software that enables the implementation of a designed relational model. Examples of RDBMS include MySQL, MS SQL, Oracle, and IBM DB2.

## RDBMS: Relational Database Management System

A Relational Database Management System (RDBMS) is a software that enables the implementation of a designed relational model. It provides tools and features to store, manage, and administrate databases using SQL for all CRUD operations.

### MySQL

MySQL is an open-source RDBMS and is one of the most popular databases. It uses SQL as its query language and follows a client-server model. In this model, the client, which can be a command-line interface (CLI) or a frontend application, uses the services provided by the MySQL server to interact with the database.

## SQL Data Types

In SQL databases, data is stored in the form of tables, and data can have different types. Here are some common data types used in SQL:

| Data Type   | Description                                      |
|-------------|--------------------------------------------------|
| CHAR        | String with a fixed size (0-255)                  |
| VARCHAR     | String with a variable size (0-255)               |
| TINYTEXT    | String with a maximum length of 255 characters    |
| TEXT        | String with a maximum length of 65,535 characters |
| BLOB        | Binary large object                              |
| INT         | Integer                                          |
| FLOAT       | Decimal with precision up to 23 digits            |
| DOUBLE      | Decimal with precision from 24 to 53 digits       |
| DATE        | Date in the format YYYY-MM-DD                     |
| DATETIME    | Date and time in the format YYYY-MM-DD HH:MM:SS   |
| BOOLEAN     | Boolean (0 or 1)                                 |
| ...         | Additional data types can exist depending on the database system |

Note: The above list is not exhaustive and may vary depending on the specific database system.

## SQL Commands

SQL commands can be categorized into several types based on their functionality:

### DDL (Data Definition Language)

DDL commands are used to define the structure of the database.

1. CREATE: Used to create tables, databases, or views.
2. ALTER TABLE: Used to modify the structure of a table, such as changing column datatypes or adding/removing columns.
3. DROP: Used to delete tables, databases, or views.
4. TRUNCATE: Used to remove all tuples from a table.
5. RENAME: Used to rename databases, tables, columns, etc.

### DRL/DQL (Data Retrieval Language / Data Query Language)

DRL/DQL commands are used to retrieve data from tables.

.
