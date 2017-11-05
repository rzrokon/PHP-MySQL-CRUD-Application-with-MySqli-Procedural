# PHP-MySQL-CRUD-Application-with-MySqli-Procedural
CRUD is an acronym for Create, Read, Update, and Delete. CRUD operations are basic data manipulation for database. We've already learned how to perform create (i.e. insert), read (i.e. select), update and delete operations in previous chapters. In this tutorial we'll create a simple PHP application to perform all these operations on a MySQL database table at one place.

# Creating the Database Table
Execute the following SQL query to create a table named employees inside your MySQL database. We will use this table for all of our future operations.

```sh

CREATE TABLE employees (
    id INT NOT NULL PRIMARY KEY AUTO_INCREMENT,
    name VARCHAR(100) NOT NULL,
    address VARCHAR(255) NOT NULL,
    salary INT(10) NOT NULL
);

```
