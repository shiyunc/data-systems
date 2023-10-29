# SQL

## SQL syntax
- SELECT: extract

Query from all columns

    SELECT * FROM table_name;

Query from a specific column

      SELECT column_name1, column_name2
      FROM table_name
      WHERE condition;

- UPDATE

        UPDATE table_name
        SET column_name1 = new_value1, 
        WHERE condition;

- DELETE

        DELETE FROM table_name 
        WHERE condition;

- INSERT INTO

        INSERT INTO table_name (column_name1, column_name2)
        VALUES (value1, value2);

- CREATE

Create Table

    CREATE TABLE table_name (
        column1 datatype,
        column2 datatype,
    );

Create Database

    CREATE DATABASE database_name;

Note: VARCHAR(string), BOOL, int, FLOAT, DATETIME

- ALTER: modify

Add

    ALTER TABLE table_name
    ADD column_name datatype;

Delete

    ALTER TABLE Customers
    DROP COLUMN Email;

Rename

    ALTER TABLE table_name
    RENAME COLUMN old_name to new_name;

<br/>
<br/>

References:
- https://www.w3schools.com/sql/sql_alter.asp

