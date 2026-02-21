# SQL-Learnings

- SQL stands for (Structured Query Language) and it is used to interact with databases such as:
  - Retrieve data
  - Analyse data
  - Define data
  - Change data
    
- What is a database?
    - It is a set of Tables in which we store structured data. The tables consists of rows and columns.
    - We retrieve the data using commands in SQL. For example, SELECT <column 1>, <column2>,...FROM <table_name>

- Schema
  - It is an additional layer that helps us to structure and organise our data. You can think of this as a folder which has different tables

- Database Management System (DBMS)
  -  We DBMS need to manage these database. In my case, i used PostgreSQL(this is DBMS - it is a software which is used to manage the database) and PgAdmin (front end graphical interface)

-  Why PostgreSQL?
    - PostgreSQL is the closest to the standard SQL
    - Most flexible and transition will be easiest
    -  Free to download and use
    -  Very propular
    -  The most advanced DBMS in the world

Keyword	Description	Syntax
SELECT	Used to select and return data		SELECT column_name FROM table_name (selecting single column)
	SELECT first_name, last_name FROM actor (multiple column)
	SELECT * from actor (all columns)
ORDER BY	Used to order results based on a column		SELECT column_name1, column_name2 FROM table_name ORDER BY column_name1
DESC	Order columns in descending order		SELECT first_name, last_name FROM actor ORDER BY first_name DESC
	SELECT first_name, last_name FROM actor ORDER BY first_name DESC, last_name (multiple column)
ASC	Order columns in descending order		SELECT first_name, last_name FROM actor ORDER BY first_name ASC
SELECT first_name, last_name FROM actor ORDER BY first_name ASC, last_name (multiple column)
SELECT DISTINCT	Used to select the distinct values in a table		SELECT DISTINCT column_name FROM table_name
	SELECT DISTINCT first_name, last_name FROM table_name ORDER BY first_name (multiple columns)
LIMIT	Used to limit the number of rows in the output. Always use at the very end of the query		SELECT first_name FROM actor ORDER BY first_name LIMIT 4
Count	Used to count the number of rows in a output. Used often in combination with grouping and filtering		SELECT COUNT (*) FROM table_name
	SELECT COUNT (first_name) FROM actor
	SELECT COUNT (DISTINCT first_name) FROM actor
		
Basics: Filtering
		
		
