📘 DBMS Lab Practical Workbook Summary

By: Fizza Ahmed (DT-23304)
Course Code: CT-261
Department: Data Science
University: NED University of Engineering & Technology


---

🔹 Lab 1: Basic SQL SELECT Statements

Use SELECT, FROM, and AS to retrieve and rename columns.

Correct SQL syntax matters (commas, aliases).

View structures with DESC tablename;

Create and run queries using .sql files.


🔹 Lab 2: Restricting and Sorting Data

Use WHERE, BETWEEN, IN, and NOT operators.

Apply sorting with ORDER BY.

Combine multiple conditions using AND / OR.

Search using LIKE and wildcards (%).

Date ranges and filtering on specific columns.


🔹 Lab 3: Single-Row Functions

Use functions like UPPER(), LOWER(), INITCAP().

Use LENGTH(), ROUND(), TRUNC(), SYSDATE.

Create calculated output like “Dream Salary” using string concatenation.

Use TO_CHAR() for formatting dates and numbers.

Use DECODE() for conditional logic like IF...ELSE.


🔹 Lab 4: Displaying Data from Multiple Tables

Practice joins: INNER JOIN, OUTER JOIN, SELF JOIN.

Retrieve related data from multiple tables.

Match employee details with department or manager info.

Label columns using AS.


🔹 Lab 5: Group Functions

Use MIN(), MAX(), SUM(), AVG(), COUNT().

Group data with GROUP BY and filter with HAVING.

Compare aggregates like highest/lowest salary.

Use nested queries for job-based or department-based aggregation.


🔹 Lab 6: Subqueries

Use single-row and multi-row subqueries.

Use ANY, ALL, IN, EXISTS.

Subqueries for comparisons (e.g., salary > avg salary).

Nested queries to filter based on other employee details.


🔹 Lab 7: Data Manipulation (DML)

Use INSERT, UPDATE, DELETE.

Understand COMMIT and ROLLBACK.

Use scripts to manage changes.

Practice updating specific rows or conditions.


🔹 Lab 8: Creating and Managing Tables

Use CREATE TABLE, ALTER TABLE, DROP TABLE.

Add/modify columns and data types.

Clone tables using CREATE TABLE new AS SELECT * FROM old;

Rename or drop columns using ALTER TABLE.


🔹 Lab 9: Constraints

Use PRIMARY KEY, FOREIGN KEY, CHECK, NOT NULL, UNIQUE.

Name constraints (my_emp_id_pk, my_emp_dept_id_fk).

View constraints with USER_CONSTRAINTS.


🔹 Lab 10: Views

Use CREATE VIEW, REPLACE VIEW, DROP VIEW.

Create READ ONLY views to restrict updates.

Views can be simple or complex (with GROUP BY, joins).

Use USER_VIEWS to inspect view definitions.



---

💡 PL/SQL Concepts

🔸 1. Declaring Variables

Use DECLARE with data types: NUMBER, VARCHAR2, BOOLEAN.

Assign values using := or DEFAULT.


🔸 2. Executable Statements

Use BEGIN ... END; for SQL logic.

Retrieve data with SELECT ... INTO.


🔸 3. Interacting with Oracle Server

Use INSERT, COMMIT inside PL/SQL blocks.

Combine multiple statements.


🔸 4. Control Structures

Use IF...THEN...ELSE, CASE for decisions.

Use loops and conditions.


🔸 5. Exception Handling

Use EXCEPTION ... WHEN to catch errors.
