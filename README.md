# Football Ticket Booking System - Database Design & SQL Queries

## 📌 Overview

This project is a database design and SQL query assignment for a Football Ticket Booking System. The system manages football fans, tournament matches, and ticket bookings while demonstrating database relationships, normalization, and SQL query writing skills.

## 🎯 Objectives

- Design an ERD with proper relationships.
- Implement Primary Keys and Foreign Keys.
- Maintain referential integrity.
- Write SQL queries using:
  - Filtering
  - Pattern Matching
  - JOIN Operations
  - Aggregation
  - Subqueries
  - NULL Handling
  - Pagination

## 🗄️ Database Schema

### Tables

1. **Users**
   - Stores football fans and ticket managers.

2. **Matches**
   - Stores match information, ticket prices, and availability status.

3. **Bookings**
   - Stores ticket purchase records linking users and matches.

### Relationships

- One User ➝ Many Bookings
- One Match ➝ Many Bookings
- Each Booking belongs to exactly one User and one Match

## 📂 Project Contents

- ERD Design
- Table Schema
- Sample Data
- SQL Query Solutions
- Theory Question Answers

## 🛠️ Technologies Used

- PostgreSQL
- SQL
- Draw.io / Lucidchart (ERD Design)

## 📜 SQL Topics Covered

- SELECT & WHERE
- LIKE / ILIKE
- COALESCE
- INNER JOIN
- LEFT JOIN / FULL JOIN
- Aggregate Functions
- Subqueries
- ORDER BY
- LIMIT & OFFSET

## 👨‍💻 Author

Md. Rejaur Rahman

## 📄 License

This project is created for educational purposes as part of the Programming Hero Level 2 Web Development Course.
