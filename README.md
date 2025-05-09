

# Library Management System

## Description

This is a relational database schema for a Library Management System. It tracks books, authors, library members, loans, categories (genres), and librarians. The design uses foreign keys to link tables and ensures data integrity with appropriate constraints (primary keys, NOT NULL, UNIQUE, etc.).

## Importing the Schema

1. Install and start MySQL.
2. Create a new database (e.g. `library_db`):

   ```sql
   CREATE DATABASE library_db;
   ```

## Entity Relationship Diagram (ERD)

![Library ERD](/library.drawio.png)

