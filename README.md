Hospital Management System

    This project contains the database schema design and implementation scripts for a Hospital Management System. 
    It is developed using Oracle SQL*Plus and demonstrates essential database concepts such as table creation,
    sequences, triggers, and entity relationships.

Files Included

    hospital_schema.sql – SQL script to:
    Create tables (Patient, Doctor, Department, Appointment)
    Define primary and foreign keys
    Create sequences and triggers to auto-generate IDs
    Insert sample data
    hospital_er_diagram.png – Entity Relationship diagram showing schema structure

Entities and Relationships
   
    Patient- Stores patient information including ID, name, date of birth, and gender.
    Department-Contains hospital departments such as Cardiology, Neurology, etc.
    Doctor-Includes doctor details and links to the respective department.
    Appointment-Records appointments, linking patients to doctors with date and time details.

The ER diagram represents the connections between these entities, ensuring referential integrity using primary and foreign key constraints.

Key Features

    Auto-generation of primary key values using sequences and triggers
    Referential integrity through foreign key constraints
    Usage of appropriate data types like DATE and VARCHAR2
    Demonstrates table creation (DDL) and data insertion (DML)
    Includes multi-row insert statements for sample data

How to Use

    Open Oracle SQL*Plus or any Oracle-compatible SQL editor
    Execute the hospital_schema.sql script to create the database schema
    View the ER diagram using hospital_er_diagram.png to understand relationships between entities

Requirements

    Oracle Database
    Oracle SQL*Plus or a compatible SQL client
