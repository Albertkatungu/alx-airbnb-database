# Airbnb Database Schema (DDL)

## Overview
This SQL script defines the **Airbnb relational database schema**, modeling users, properties, bookings, payments, and reviews. It ensures data integrity, efficiency, and scalability for an Airbnb-like platform.

## Tables Created
1. **users** – Stores guest and host information.
2. **properties** – Details of each listed property.
3. **bookings** – Tracks reservations made by users.
4. **payments** – Handles booking payment records.
5. **reviews** – Contains feedback and ratings for bookings.

## Key Features
- Primary and Foreign Key constraints ensure relational integrity.
- Indexed columns improve search and query performance.
- Cascading deletes maintain referential consistency.
- Timestamps and status fields simulate real-world workflows.

## Files
- `schema.sql` → SQL script for creating the database schema.
- `README.md` → This documentation.

## Author
**Albert Kay** – ALX Software Engineering Program
