Online Bookstore Data Analysis (SQL Project)

Project Overview
This project involves designing and analyzing a relational database for an online bookstore. The objective is to manage raw data (Books, Customers, and Orders), establish 
table relationships (Primary and Foreign Keys), and write complex SQL queries to extract meaningful business insights such as revenue generation, inventory management, and 
customer ordering patterns.

Tech Stack
Database: PostgreSQL
Tools: pgAdmin 4
Language: SQL (DDL, DML and DQL)

Database Schema (ERD Structure)
The database consists of three main tables:

BOOKS: Stores book details including Title, Author, Genre, Published Year, Price, and available Stock.

CUSTOMERS: Stores customer demographics like Name, Email, Phone, City, and Country.

ORDERS: Acts as the transactional table linking Books and Customers, recording Order Date, Quantity, and Total Amount.

Key Business Problems Solved
Through this project, I executed 20 structured SQL queries (Basic to Advanced) to solve real-world business scenarios:

Inventory Management: Identified books with the lowest stock dynamically using subqueries and calculated the remaining stock after fulfilling all orders using COALESCE and LEFT JOIN.

Revenue Analysis: Calculated total revenue generated and identified the highest-spending customers.

Customer Behavior: Filtered customers with multiple orders and tracked customer geographic distribution.

Sales Trends: Discovered the most frequently ordered books and identified top-selling authors and genres.

Advanced SQL Concepts Applied
Joins (INNER JOIN, LEFT JOIN)

Aggregate Functions (SUM, AVG, COUNT, MIN, MAX)

Grouping & Filtering (GROUP BY, HAVING, WHERE)

Dynamic Subqueries

Data Import via COPY command

How to Use
Clone this repository.

Create the tables using the CREATE TABLE scripts.

Import the provided CSV files (Books.csv, Customers.csv, Orders.csv) into your database.

Execute the SQL queries to view the business insights.
