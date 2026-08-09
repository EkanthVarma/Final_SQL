# Food Delivery  System

## Project Overview
The Food Delivery System is a relational database project developed using MySQL.
This project is designed to manage food delivery operations such as maintaining restaurants, menu items, customers, delivery agents, orders, order items, payments, and ratings.

The database demonstrates the implementation of:

- Table creation
- Primary and foreign keys
- Data insertion
- Relationships between tables
- SQL queries of different difficulty levels

## Technologies Used

- MySQL
- SQL

## Database Tables
The project contains the following tables:

- Customers
- Restaurants
- MenuItems
- DeliveryAgents
- Orders
- OrderItems
- Payments
- Ratings

## Relationships

- One customer can place multiple orders
- One restaurant can receive multiple orders
- One restaurant can offer multiple menu items
- One delivery agent can deliver multiple orders
- One order can contain multiple order items
- One menu item can appear in multiple order items
- One order has exactly one payment
- One order can have at most one rating
- One customer can write multiple ratings
- One restaurant can receive multiple ratings

## SQL Queries Included

**Easy Level Queries**
Queries using:
- WHERE clause
- Operators
- BETWEEN
- LIKE

**Intermediate Level Queries**
Queries using:
- Aggregate Functions
  - AVG()
  - MAX()
  - COUNT()
  - SUM()
- GROUP BY

**Hard Level Queries**
Queries using:
- JOINS
- GROUP BY
- HAVING
- ORDER BY
- Window Functions (RANK, PARTITION BY)

## Features

- Proper relational database design
- Use of primary and foreign keys
- Data analysis using SQL queries
- ER Diagram included
- Sample records inserted for testing

## Learning Outcomes
Through this project, the following concepts were practiced:

- Database normalization
- SQL query writing
- Table relationships
- Aggregate functions
- Joins and relational analysis
- ER diagram design

## Author
Developed as part of SQL database practice and academic learning.

===================================================================================================================================================================
# Student Management System

## Project Overview

The Student Management System is a relational database project developed using MySQL.

This project is designed to manage student academic information such as students, subjects, exams, and marks.

The database demonstrates the implementation of:

- Table creation
- Primary and foreign keys
- Data insertion
- Relationships between tables
- SQL queries of different difficulty levels

## Technologies Used

- MySQL
- SQL

## Database Tables

The project contains the following tables:

- Students
- Subjects
- Exams
- Marks

## Relationships

- One student can have multiple marks
- One subject can have multiple marks
- One exam can contain marks for multiple students
- Each mark belongs to one student
- Each mark belongs to one subject
- Each mark belongs to one exam

## SQL Queries Included

**Easy Level Queries**

Queries using:

- SELECT
- WHERE
- Comparison Operators
- ORDER BY
- BETWEEN

**Intermediate Level Queries**

Queries using:

- JOIN
- Aggregate Functions
  - AVG()
  - MAX()
  - COUNT()
  - SUM()
- GROUP BY

**Hard Level Queries**

Queries using:

- JOINS
- GROUP BY
- HAVING
- Subqueries
- CASE Statements
- Aggregate Functions

## Features

- Proper relational database design
- Use of primary and foreign keys
- Student academic record management
- Data analysis using SQL queries
- ER Diagram included
- Sample records inserted for testing

## Learning Outcomes

Through this project, the following concepts were practiced:

- Database design
- SQL query writing
- Table relationships
- Primary and foreign keys
- Aggregate functions
- Joins and relational analysis
- Subqueries
- CASE statements
- ER diagram design

## Author

Developed as part of SQL database practice and academic learning.
