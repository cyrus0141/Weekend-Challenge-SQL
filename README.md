# Weekend-Challenge-SQL
creating a database to manage a library's book collection. The database should include tables for books, authors, and borrowers. Design the database schema and create the necessary tables to store this information.

Instructions:

Create a new database in MySQL Workbench called "LibraryDB."

Design and create the following tables:

Books table with the following columns:

book_id (Primary Key)
title
author_id (Foreign Key to the Authors table)
publication_year
ISBN
Authors table with the following columns:

author_id (Primary Key)
first_name
last_name
Birth_year


Borrowers table with the following columns:

borrower_id (Primary Key)
first_name
last_name
Email

Define appropriate data types and constraints for each column.
Establish the necessary relationships between the tables using foreign keys. Ensure that the author_id in the Books table is a foreign key that references the author_id in the Authors table.
After creating the tables and relationships, insert at least two sample records into each table to demonstrate how the database would be used.
Write and execute a SQL query to retrieve a list of books with their titles, authors' full names, and publication years.
