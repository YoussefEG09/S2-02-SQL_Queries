🗃️ SQL Practice Projects

This repository contains MySQL practical exercises focused on designing relational databases and executing queries of varying complexity.

It includes two main projects:

🏪 Store → Product and manufacturer management.

🎓 University → Academic management of students, professors, and courses.

🏪 Project 1: “Store” Database
📋 Description

The Store database simulates a commercial environment where technological products and their respective manufacturers are stored.
Its goal is to practice data selection, filtering, grouping, subqueries, and basic SQL functions.

🧱 Database Structure

manufacturer

code

name

product

code

name

price

manufacturer_code (foreign key → manufacturer)

🧩 Types of Queries Performed

Basic selection queries (SELECT, WHERE, ORDER BY)

Queries with column aliases and arithmetic operations

Use of text and numeric functions (UPPER, LOWER, ROUND, TRUNCATE)

Queries with aggregations and grouping (COUNT, GROUP BY, DISTINCT)

Ordered and limited results (ORDER BY, LIMIT)

Queries with JOINs between related tables

Queries with nested subqueries

Use of multiple conditions (AND, OR, IN)

Exercises with LEFT JOIN to detect unlinked records

🎓 Project 2: “University” Database
📋 Description

The University database manages academic information for a university environment.
It includes students, professors, departments, degrees, subjects, and academic years.
The objective is to practice more advanced queries with multiple relationships and logical conditions.

🧱 Database Structure

person → General data for students and professors

professor → Links professors to departments

department → Defines academic departments

subject → Stores information about individual courses

degree → Represents academic programs

academic_year → Defines school years

student_enrolls_subject → Links students, subjects, and academic years

🧩 Types of Queries Performed

Basic selection and filtering (SELECT, WHERE)

Queries with sorting and conditional filters (ORDER BY, IS NULL, LIKE)

Multi-table queries with INNER JOIN, LEFT JOIN, and RIGHT JOIN

Aggregations and grouping (COUNT, SUM, GROUP BY, HAVING)

Queries using subqueries to retrieve related data

Use of date functions (YEAR, MIN, MAX)

Queries to detect professors without subjects or departments without professors

Queries combining foreign keys and aliases

Advanced ordering using multiple criteria

⚙️ Technologies Used

MySQL 8.0+

Workbench / phpMyAdmin

Git & GitHub for version control
