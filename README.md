# Hospital Management System

This project contains the **database schema design** and **implementation scripts** for a Hospital Management System.  
It is developed using **Oracle SQL\*Plus** and demonstrates essential database concepts such as:

- Table creation (DDL)
- Sequences
- Triggers
- Entity relationships (via primary and foreign keys)
- Sample data insertion (DML)

---

##  Files Included

- **`hospital_schema.sql`** – SQL script to:
  - Create tables (`PATIENT`, `DOCTOR`, `DEPARTMENT`, `APPOINTMENT`)
  - Define primary and foreign keys
  - Create sequences and triggers to auto-generate IDs
  - Insert sample data using `INSERT ALL`

- **`hospital_er_diagram.png`** – Entity-Relationship (ER) diagram showing the schema structure

---

##  Entities and Relationships

- **PATIENT**  
  Stores patient details including ID, name, date of birth, and gender.

- **DEPARTMENT**  
  Contains hospital departments such as Cardiology, Neurology, Oncology, etc.

- **DOCTOR**  
  Includes doctor details and links each doctor to their respective department.

- **APPOINTMENT**  
  Records patient appointments, linking patients and doctors along with appointment date and diagnosis.

The **ER diagram** visualizes the relationships between these entities, ensuring referential integrity via **foreign key constraints**.

---

##  Key Features

-  **Auto-generation** of primary key values using `SEQUENCE` and `TRIGGER`
-  **Referential integrity** maintained through foreign key constraints
-  Use of appropriate data types like `VARCHAR2` and `DATE`
-  Multi-row `INSERT ALL` statements for efficient data loading
-  Demonstrates both **DDL** (Data Definition Language) and **DML** (Data Manipulation Language)

---

##  How to Use

1. Open **Oracle SQL\*Plus** or any Oracle-compatible SQL client.
2. Run the `hospital_schema.sql` script to create all tables and insert sample data.
3. Use the `hospital_er_diagram.png` to understand relationships visually.

---

##  Requirements

- Oracle Database (any edition)
- Oracle SQL\*Plus or any SQL client that supports Oracle syntax

---

##  Learning Outcomes

- Understand how to use `SEQUENCE` and `TRIGGER` for automated key generation.
- Practice designing normalized database schemas with foreign key constraints.
- Perform structured data entry using multi-row `INSERT ALL`.
- Visualize entity relationships using an ER diagram.

---



