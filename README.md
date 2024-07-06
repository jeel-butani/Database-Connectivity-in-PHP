# Database-Connectivity-in-PHP  

This repository contains the implementation examples for connecting PHP to MySQL and MongoDB databases, as outlined in the blog "PHP Database Connectivity: MySQLi, PDO, and MongoDB".
[For More details read the Blog(DBMS)](https://github.com/jeel-butani/DBMS-An-In-Depth-Guide)
## Overview

PHP is a popular server-side scripting language designed specifically for web development. It is widely used for creating dynamic and interactive websites. One of the key features of PHP is its ability to interact with databases, making it an essential tool for web developers.

### Connecting to MySQL Databases
[For More details read the Blog(Sql)](https://github.com/venishaparmar/Sql-vs-NoSql)
PHP provides two main ways to connect to a MySQL database:
1. **MySQLi (MySQL Improved)**: An enhancement of the original MySQL extension, offering both procedural and object-oriented interfaces.
2. **PDO (PHP Data Objects)**: A database access layer providing a uniform method of access to multiple databases, supporting MySQL, PostgreSQL, SQLite, and others.

#### Advantages of MySQLi and PDO

- **PDO supports multiple database systems**, whereas MySQLi works only with MySQL.
- **Prepared Statements**: Both MySQLi and PDO support prepared statements, which help in preventing SQL injection attacks, and enhancing web application security.
- **Object-Oriented and Procedural API**: MySQLi supports both object-oriented and procedural programming, whereas PDO is purely object-oriented.
- **Exception Handling**: PDO provides a robust mechanism for handling exceptions, making error handling more straightforward and effective.

#### When to Use MySQLi or PDO

- **Use MySQLi if**:
  - You are sure your application will only ever need to connect to a MySQL database.
  - You prefer a simpler, potentially more performant connection method for MySQL databases.
  - You want to use either a procedural or object-oriented approach in your code.

- **Use PDO if**:
  - You need to support multiple types of databases (e.g., MySQL, PostgreSQL, SQLite).
  - You want a consistent API for database interactions, which can make it easier to switch databases in the future.
  - You prefer object-oriented programming and the advanced features provided by PDO, such as better exception handling.

### Connecting to NoSQL Databases: MongoDB
[For More details read the Blog(NoSql)](https://github.com/venishaparmar/Sql-vs-NoSql)
While MySQL is a relational database, MongoDB is a NoSQL database that stores data in a flexible, JSON-like format. PHP provides support for MongoDB through the MongoDB PHP library.

#### Installing MongoDB PHP Library

To use MongoDB with PHP, you need to install the MongoDB PHP driver using Composer:
```bash
composer require mongodb/mongodb
```
[For More details read the Blog](https://medium.com/@butanijeel1/database-connectivity-in-php-3c6956f0e76f)

