# SQL-Tasks

Objective:
Design a structured relational database using MySQL Workbench. This includes creating tables, defining primary and foreign keys, and generating an ER diagram through reverse engineering.

Domain: Library Management System
The system is designed to manage data for a library, including books, authors, members, and borrowing records.

Included Files:

SQL Task_1.sql – SQL script to create the database schema

SQL Task 1.png – ER diagram of the schema generated via MySQL Workbench

Tools Used:

MySQL Workbench

To create and run SQL scripts

To reverse engineer and generate ER diagram

Database Tables:

Author – (author_id, name)

Book – (book_id, title, publication_year)

Member – (member_id, name, email)

Borrow – (borrow_id, book_id, member_id, borrow_date, return_date)

Book_Author – (book_id, author_id) → For many-to-many relationship between books and authors

How to Run:

Open MySQL Workbench

Create a schema (e.g., LibraryDB)

Run the SQL Task_1.sql script

Go to Database > Reverse Engineer

Select the schema and let it auto-generate the ER diagram

Export the diagram as PNG

Outcome:

A normalized and structured library database schema

Proper use of primary and foreign keys

ER diagram for visual understanding of the schema
