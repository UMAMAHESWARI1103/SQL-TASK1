Hospital Management System
Overview
This project contains the database schema design and implementation scripts for a Hospital Management System. The schema is developed using Oracle SQL*Plus and demonstrates creating tables, sequences, triggers, and relationships essential for hospital operations.

Entities and Relationships
Patient: Stores patient details including ID, name, date of birth, and gender.

Department: Stores hospital departments such as Cardiology, Neurology, etc.

Doctor: Stores information about doctors, linked to their department.

Appointment: Records scheduled appointments linking patients to doctors with details.

The ER diagram illustrates how these entities are related, ensuring data integrity through primary and foreign key constraints.

Files Included
hospital_schema.sql - SQL script to create tables, sequences, triggers, and insert sample data.

hospital_er_diagram.png - Entity Relationship diagram visualizing the database schema.

Key Features
Use of Sequences and Triggers to auto-generate primary key values.

Composition of Foreign Key Constraints to maintain referential integrity.

Demonstrates DDL commands for table creation and modification.

Sample multi-row insertions for populating initial data.

Proper use of data types including DATE and VARCHAR2.

Usage
Run the hospital_schema.sql script in Oracle SQL*Plus or compatible environment.

Refer to the ER diagram (hospital_er_diagram.png) to understand entity relationships.

Modify or extend the schema as needed for further hospital management features.
