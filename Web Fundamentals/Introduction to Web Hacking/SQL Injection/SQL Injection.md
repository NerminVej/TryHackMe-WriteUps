### Learn how to detect and exploit SQL Injection vulnerabilities

## Task 1 Brief

SQL injection causes malicious queries to bbe executed.

- What does SQL stand for?
> Structured Query Language

## Task 2 What is a Database?

A database stores electronically collections of data in an organised manner and is controlled by a DBMS (Database Management System).
There are Relational and Non-Relational databbases.

A table is made up of columns and rows. It's like a grid.


- What is the acronym for the software that controls a database?
> DBMS

- What is the name of the grid-like structure which holds the data?
> Table


## Task 3 What is SQL?

### SELECT

Is used to retrieve data from the database.
`select * from users;`

The star means that we tell SQL to get ALL values for "users"

`select username,password from users;`
This means that we want "username" and "password" this time instead of everything.

### LIMIT
`select * from users LIMIT 1;`
With LIMIT we can set how many row we should get returned. LIMIT 1 means we get one row back.

### WHERE
`select * from users where username='admin';`
With this command we get all "users" where the username="admin".
With the WHERE command we can be more specific in our search

`select * from users where username='admin' and password='p4ssword';`
We can also add an and or != to be even more specific. It is like with logical operations in programming.

### WILDCARD
`select * from users where username like 'a%';`
All the rows get returned that have a username that starts with "a".

`select * from users where username like '%mi%';`
All usernames that have a "mi" within them.

### UNION
`SELECT name,address,city,postcode from customers UNION SELECT company,address,city,postcode from suppliers;`
We can access the data of two tables and combine them into one.

### INSERT
`insert into users (username,password) values ('bob','password123');`
We can use INSERT to insert a new row of data into the table.
Here in this example its "bob" with the password "password123".

### UPDATE
`update users SET username='root',password='pass123' where username='admin';`
We can update the information of an existing user inside of the table with UPDATE.

### DELETE
`delete from users where username='martin';`
We can delete entries from the table with DELETE.

- What SQL statement is used to retrieve data?
> SELECT

- What SQL clause can be used to retrieve data from multiple tables?
> UNION

- What SQL statement is used to add data?
> INSERT

## Task 4 What is SQL Injection?



