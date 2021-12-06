# CREATE query

- **CREATE DATABASE**

  **Syntax:** ` CREATE DATABASE database_name;`
  
  e.g: ` CREATE DATABASE ruchi_db;`

- **CREATE TABLE:** The CREATE TABLE statement is used to create a table in SQL. It comprises of rows and columns.

  **Syntax:** 
  
 ``` sh
 
CREATE TABLE table_name
(
column1 data_type(size),
column2 data_type(size),
column3 data_type(size),
....and so on...
);

```

e.g : Below given table will create a table called Progress with 3 columns called Day, Topic_covered & Subject_name

```sh

CREATE TABLE Progress
(
Day int(3),
Topic_covered varchar(100),
Subject_name varchar(100),
.....
);

```
