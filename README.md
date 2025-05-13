# 🎓 Student Records Database

A MySQL relational database system to manage students, departments, addresses, courses, and enrollments. This project demonstrates the use of entity relationships, constraints, and normalization (1NF to 3NF) in a student management system.

---

## 📝 Description

This project simulates a student information system using SQL. It includes:

- **Departments** offering various courses
- **Students** belonging to departments
- **Addresses** associated with each student (1-to-1)
- **Courses** students can enroll in (many-to-many)
- A complete ERD with well-defined foreign key relationships and normalization principles.

---

## 🚀 Setup Instructions

### 1. Prerequisites
- MySQL Server installed
- MySQL Workbench or command-line access
- Git (optional, for cloning the repo)

### 2. Run the SQL Script

1. Open **MySQL Workbench**
2. Create the database:
    ```sql
    CREATE DATABASE IF NOT EXISTS StudentRecordsDB;
    USE StudentRecordsDB;
    ```
3. Run the SQL file `student_records.sql` to create all tables and constraints.

 Tip: After running the script, refresh the SCHEMAS tab and make sure `StudentRecordsDB` is selected.

### 3. View the Tables
Use the following command to confirm:
```sql
SHOW TABLES;
