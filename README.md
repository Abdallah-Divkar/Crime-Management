# Crime Database Management System

This project demonstrates the implementation of a crime database management system using SQL. It simulates a realistic scenario by managing entities like crimes, criminals, victims, officers, and departments while maintaining relationships between them.

## Features

- **Entity Representation**:
  - Contacts, Departments, Crimes, Criminals, Victims, Officers, Cases, and Weapons.
- **Relationships**:
  - Foreign key constraints establish relationships between entities.
  - Checks and validations ensure data integrity.
- **Sample Scenarios**:
  - Scenarios with realistic data to demonstrate database functionality.
- **Data Management**:
  - Insert, modify, and delete operations on the database.

## Table Overview

1. **Contact**: Stores contact information for individuals and organizations.
2. **Department**: Represents police departments and their details.
3. **Crime**: Maintains records of crimes, including types, dates, and locations.
4. **Criminal**: Tracks information about individuals involved in crimes.
5. **Case**: Details the legal proceedings associated with criminals.
6. **Weapon**: Records weapons used in crimes.
7. **Officer**: Stores details about law enforcement officers.
8. **Victim**: Tracks details of individuals affected by crimes.

## Constraints and Validations

- Primary keys to uniquely identify records.
- Foreign keys to enforce relationships between entities.
- Check constraints for data validation (e.g., gender, rank, and status).

## Usage

1. **Database Setup**:
   - Run the table creation scripts to set up the database schema.
2. **Data Insertion**:
   - Execute the data insertion scripts to populate tables with sample data.
3. **Querying**:
   - Use SQL queries to analyze data or test relationships.
4. **Dropping Tables**:
   - Use the provided drop table scripts to reset the database.

## Scenarios

The project includes four scenarios that populate the database with sample data, simulating different criminal cases. Each scenario showcases:

- The involvement of multiple entities in a crime.
- The relationships and dependencies between entities.
- Realistic data entries for crimes, criminals, victims, and officers.

## Prerequisites

- SQL-compatible database software (e.g., Oracle, MySQL, PostgreSQL).
- SQL knowledge to execute the scripts and queries.

## How to Run

1. Clone the repository:
   ```bash
   git clone <repository_url>
