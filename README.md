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
![dbms 1](https://github.com/vikashsenthil21/I2_DBMS/assets/119433834/a7706f51-39df-4726-b8da-ed95c1c81fdc)

### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
alter table student add department varchar(15);

### OUTPUT:

![dbms 2](https://github.com/vikashsenthil21/I2_DBMS/assets/119433834/d2929252-11e9-4e98-9706-cc358a6cb4e8)


### 3) Drop the student table
 
### SQL QUERY: 
drop table student;

### OUTPUT:
![dbms 3](https://github.com/vikashsenthil21/I2_DBMS/assets/119433834/a1d7851e-2213-4e7e-8eeb-7ee0e7587422)


### 4) Delete the student table using truncate keyword

### SQL QUERY: 
truncate table student;

### OUTPUT:
 ![dbms 4](https://github.com/vikashsenthil21/I2_DBMS/assets/119433834/5e25aab1-2c5b-4f59-a217-cbaa4f14a8c5)
### 5) Rename the
student table to mystudent

### SQL QUERY: 
rename table student to mystudent;

### OUTPUT:
![dbms 5](https://github.com/vikashsenthil21/I2_DBMS/assets/119433834/16114fd4-6c26-4042-8466-04688cb1bc61)

