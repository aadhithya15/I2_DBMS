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
create table student(rollno numeric(10),name char(10),age numeric(5),address varchar(25),phoneno numeric(15));

### OUTPUT:
![1](https://github.com/Divya110205/I2_DBMS/assets/119404855/960e66b8-fd34-420c-ac25-840488ccc6ea)

### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
alter table student add department varchar(15);

### OUTPUT:
![2](https://github.com/Divya110205/I2_DBMS/assets/119404855/6b9b4233-8203-4217-bf24-2d2495386908)

### 3) Drop the student table
 
### SQL QUERY: 
drop table student;

### OUTPUT:
![3](https://github.com/Divya110205/I2_DBMS/assets/119404855/e9ec15a1-9208-4344-bd40-56f9b5f52a29)

### 4) Delete the student table using truncate keyword

### SQL QUERY: 
truncate table student;

### OUTPUT:
![4](https://github.com/Divya110205/I2_DBMS/assets/119404855/1e31eef1-d37f-4bc1-b5c2-0d05bef01c0b)

### 5) Rename the student table to mystudent

### SQL QUERY: 
rename table student to mystudent;

### OUTPUT:
![5](https://github.com/Divya110205/I2_DBMS/assets/119404855/fc4ff924-619e-4531-ac59-4a9f9048f8b0)
