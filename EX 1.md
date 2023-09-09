# EXP NO 1: DATA DEFINITION LANGUGE COMMANDS IN RDBMS

## AIM:
To create a student database and execute DDL queries using SQL.


## DDL (Data Definition Language)
<div align="justify">
DDL or Data Definition Language actually consists of the SQL commands that can be used to define the database schema. It simply deals with descriptions of the database schema and is used to create and modify the structure of database objects in the database. DDL is a set of SQL commands used to create, modify, and delete database structures but not data. These commands are normally not used by a general user, who should be accessing the database via an application.
</div>
 
## List of DDL commands: 
<div align="justify">
CREATE: This command is used to create the database or its objects (like table, index, function, views, store procedure, and triggers).
DROP: This command is used to delete objects from the database.
ALTER: This is used to alter the structure of the database.
TRUNCATE: This is used to remove all records from a table, including all spaces allocated for the records are removed.
RENAME: This is used to rename an object existing in the database.
</div>

## Query:
### 1) Create a table student with the following fieds rollno,name,age,address,phoneno.

### SQL QUERY: 
```python
CREATE TABLE students(rollno INT,name VARCHAR(100),age INT,address VARCHAR(100),phoneno VARCHAR(15));
```
![image](https://github.com/JEGADEESH07/I2_DBMS/assets/113497131/d12b30b6-4cc4-4696-98df-0fa16fdddd0e)


### OUTPUT:

### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
```python
INSERT INTO students(rollno, name, age, address, phoneno) VALUES (1, 'John', 20, 'CHENNAI', '9153657854');
INSERT INTO students(rollno, name, age, address, phoneno) VALUES (2, 'SMITH', 25, 'TRICHY', '9746441548');
```
### OUTPUT:
![image](https://github.com/JEGADEESH07/I2_DBMS/assets/113497131/03e8c0e3-d1cc-4b9c-adc1-285ee4eacc58)



### 3) Drop the student table
 
### SQL QUERY: 
```python
DROP TABLE mystudent;
```

### OUTPUT:
![image](https://github.com/JEGADEESH07/I2_DBMS/assets/113497131/90708111-dffb-48cb-b10b-aa78c3533aa3)


### 4) Delete the student table using truncate keyword

### SQL QUERY: 
```python
TRUNCATE TABLE mystudent;
```

### OUTPUT:
![image](https://github.com/JEGADEESH07/I2_DBMS/assets/113497131/226898db-fcba-41b1-9904-3606e5cc804f)



### 5) Rename the student table to mystudent

### SQL QUERY: 
```python
ALTER TABLE students RENAME TO mystudent;
```

### OUTPUT:
![image](https://github.com/JEGADEESH07/I2_DBMS/assets/113497131/5fb20f8b-87f8-434a-9d05-36c03abec3ce)
