
# Clinic Booking System

##  Project Title
Clinic Booking System - Relational Database using MySQL

##  Description
This project implements a complete relational database for managing a clinic's appointments, patients, doctors, medical records, and specializations. It captures real-world relationships including:
- Many-to-many doctor specializations
- Appointments linking patients and doctors
- Medical records for each appointment

Built with pure SQL using proper constraints (PK, FK, NOT NULL, UNIQUE) and designed to be normalized and efficient.

##  How to Setup / Run

1. Open your MySQL client (e.g., MySQL Workbench, phpMyAdmin, command line).
2. Create a new database:

```sql
CREATE DATABASE clinic_booking_system;
USE clinic_booking_system;
```

3. Import the provided SQL file:

```bash
SOURCE path/to/clinic_booking_schema.sql;
```

Replace `path/to/clinic_booking_schema.sql` with the actual path to the file you downloaded.

##  ERD Screenshot
![ERD Screenshot](https://drive.google.com/file/d/1Ml5KGSamPeD1s2mwoMlM8wC0tAVfEfwU/view?usp=sharing)

##  File Contents

- `clinic_booking_schema.sql`: Full database schema for the Clinic Booking System.
- `README.md`: Project overview and setup instructions.

##  Author
Cyusa Alain
