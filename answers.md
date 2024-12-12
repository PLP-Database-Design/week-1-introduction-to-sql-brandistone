---State and Explain the components of a DBMS(Database Management System)

Software: Manages the database and allows users to interact with it. This includes the operating system, database software, network software, and applications. 
Hardware: The physical infrastructure, such as computers and storage devices. 
Data: The raw facts and information that are stored in databases. 
Procedures: The instructions that govern how the DBMS is designed and used. This includes instructions for setup, login, logout, data backups, and reports. 
Database access language: A simple language that allows users to write commands to access, insert, update, and delete data. 



---What is a relational database? Give 4 examples

Stores data in tables that can be linked by relationships: For example MySQL, PostgreSQL, MariaDB, Microsoft SQL Server, and Oracle Database.

---State and Explain three classifications of SQL?

DQL (Data Query Language)
Function: DQL is used for querying or retrieving data from the database.

DML (Data Manipulation Language)
Purpose: DML is used for manipulating data within the database. It includes operations such as inserting, updating, or deleting data.

DDL (Data Definition Language)
Purpose: DDL is used to define and manage database schema (structure). It is used to create, alter, or delete database objects like tables, views, indexes, and schemas.


---What is the difference between a Primary Key and a Foreign Key?

A Primary Key: is a column or a combination of columns in a table that uniquely identifies each row in the table while a  Foreign Key is a column or a set of columns in a table that is used to establish a link between the data in two tables. It is a reference to the Primary Key in another table.


---What is an Entity-Relationship Diagram?

An Entity-Relationship Diagram (ERD): is a visual representation of the entities within a system and the relationships between those entities. 

---What are the advantages of relational databases?

Data Integrity Constraints: Relational databases ensure data integrity by enforcing constraints such as primary keys, foreign keys, unique constraints, and check constraints. This ensures that the data remains accurate, consistent, and reliable across the database.

Powerful Querying: Relational databases use SQL, a standardized and powerful language for querying and manipulating data. SQL allows users to perform complex operations like filtering, grouping, sorting, and joining tables, which makes data retrieval flexible and efficient.

Horizontal and Vertical Scaling: Relational databases can be scaled both horizontally (adding more machines) and vertically (increasing the power of existing machines) to handle increasing data volume.

Backup Solutions: Relational databases offer built-in support for backing up data and creating restore points.

---State four types of data type used to store data in tables?

a) Integer (INT)

Description: Used to store whole numbers (positive and negative) without any decimal points.

b) Character/String (CHAR, VARCHAR)

Description: Used to store alphanumeric characters (letters, numbers, symbols).
CHAR: Fixed length string.
VARCHAR: Variable length string.

c) Decimal/Float (DECIMAL, FLOAT, DOUBLE)

Description: Used to store numbers with decimal points (real numbers).
DECIMAL: Fixed precision number with exact storage for decimal values.
FLOAT/DOUBLE: Approximate numeric values with floating decimal points.

d) Date and Time (DATE, DATETIME, TIMESTAMP)

Description: Used to store date and time information.
DATE: Stores the date (year, month, day).
DATETIME: Stores both date and time (year, month, day, hour, minute, second).
TIMESTAMP: Stores both date and time with automatic updates.


---What is the purpose of a database management system (DBMS)?

Data Storage, Retrieval, and Management: The DBMS allows for the storage, modification, and retrieval of data in a structured and organized way. It ensures that data is stored in tables, making it easy to access and update. It also handles data integrity and consistency when multiple users access the database simultaneously.

Data Security and Access Control: A DBMS provides features like user authentication and authorization to control access to the data. It ensures that only authorized users can perform certain actions, such as reading, writing, or modifying data.



