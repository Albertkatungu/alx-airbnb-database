# AirBnB Database Schema - Task 2

## Overview
This directory contains the complete Database Definition Language (DDL) scripts for the AirBnB database schema as part of the ALX Airbnb Database Module.

## Files Description

### 1. schema.sql
**Main schema creation script**
- Creates all database tables with proper data types
- Defines primary keys, foreign keys, and basic constraints
- Implements ENUM types for fixed value sets
- Sets up default values and automatic timestamps

### 2. indexes.sql
**Performance optimization indexes**
- Creates strategic indexes for common query patterns
- Optimizes search, filter, and join operations
- Includes composite indexes for complex queries
- Covers all foreign key columns and frequently searched fields

### 3. constraints.sql
**Enhanced data integrity constraints**
- Adds business logic validation constraints
- Implements data format validation (email, phone)
- Includes advanced constraint functions
- Ensures data quality and business rule enforcement

### 4. triggers.sql
**Automated database triggers**
- Implements automatic calculated fields
- Enforces business rules at database level
- Maintains data consistency automatically
- Provides audit trail functionality

## Database Features

### 🏗️ Schema Design
- **6 Main Tables**: Users, Property, Booking, Payment, Review, Message
- **UUID Primary Keys**: Ensures global uniqueness
- **Proper Normalization**: 3NF compliant design
- **Cascade Deletes**: Maintains referential integrity

### 🔒 Data Integrity
- **CHECK Constraints**: Validates business rules
- **NOT NULL Constraints**: Ensures data completeness
- **UNIQUE Constraints**: Prevents duplicate data
- **Foreign Keys**: Maintains relationship integrity

### ⚡ Performance
- **Strategic Indexing**: Optimizes query performance
- **Composite Indexes**: Speeds up complex searches
- **Partial Indexes**: Reduces index size where appropriate

### 🔄 Automation
- **Automatic Timestamps**: created_at, updated_at fields
- **Calculated Fields**: Automatic price calculations
- **Business Logic**: Enforced at database level

## Installation Instructions

### Step 1: Create Database
```sql
CREATE DATABASE airbnb;
\c airbnb;
