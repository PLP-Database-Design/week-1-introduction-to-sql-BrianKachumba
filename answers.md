1.State and Explain the components of a DBMS(Database Management System) A DBMS is a software system designed to manage databases. Its main components are: 1. Database Engine: The core service for storing, managing, and retrieving data. 2. Database Schema: The structure of the database, which defines tables, relationships, and data types. 3. Query Processor: It interprets and executes queries in a database, usually in SQL. 4. Transaction Manager: Ensures that database operations are performed correctly and handles transactions. 5. Database Interface: Allows users and applications to interact with the database. 6. Data Dictionary: Stores metadata (information about data structure) for the database. 2. 2. What is a relational database? Give 4 examples. A relational database stores data in tables that are related to each other through keys. The relationships between tables are maintained through foreign keys and primary keys. Examples of relational databases:

MySQL
PostgreSQL
Microsoft SQL Server
Oracle Database
3. State and Explain three classifications of SQL?

DDL (Data Definition Language): Used to define and manage database structure, such as CREATE, ALTER, DROP.
DML (Data Manipulation Language): Used for managing and manipulating data in the database, such as INSERT, UPDATE, DELETE.
DCL (Data Control Language): Used to control access to data, such as GRANT, REVOKE.
4. What is the difference between a Primary Key and a Foreign Key?

Primary Key: A unique identifier for each record in a table. It cannot be NULL and must be unique within the table.
Foreign Key: A column or a set of columns that is used to create a link between two tables. It refers to the primary key in another table.
What is an Entity-Relationship Diagram? An Entity-Relationship Diagram (ERD) is a visual representation of the entities in a database and the relationships between them. It helps in designing the structure of a database and shows how different entities interact with one another.

5. What are the advantages of relational databases?

• Data Integrity: Ensures the accuracy and consistency of data through constraints like primary keys and foreign keys. • Scalability: Can handle large amounts of data and support the growth of the database over time. • Flexibility: Allows complex queries and modifications. • Security: Provides features like access control and data encryption to protect data.

6. State four types of data type used to store data in tables? 1. INT: Used to store integer values. 2. VARCHAR: Used to store variable-length strings. 3. DATE: Used to store date values (e.g., YYYY-MM-DD). 4. FLOAT: Used to store floating-point numbers.

7. What is the purpose of a database management system (DBMS)? The purpose of a DBMS is to efficiently manage data by:

Providing a way to store, retrieve, and manipulate data.
Ensuring data security, integrity, and consistency.
Allowing users and applications to interact with the data in a controlled environment.
Supporting multi-user access to data while maintaining consistency and handling transactions.