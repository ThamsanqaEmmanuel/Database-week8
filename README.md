# Database-week8

# 🎓 Student Records Management System

## 📘 Description

The **Student Records Management System** is a SQL-based relational database project designed to manage and organize academic data for educational institutions. It maintains detailed records of students, departments, courses, instructors, enrollments, attendance, payments, and exams. The system uses proper table relationships and foreign key constraints to ensure data integrity and consistency.

## 🛠️ How to Run / Setup the Project

Follow these steps to set up and run the project on your local machine:

1. **Clone the Repository**
   Terminal:
   git clone https://github.com/ThamsanqaEmmanuel/Database-week8.git
   cd Database-week8
Open Your SQL Environment
Launch your preferred SQL management tool such as:

MySQL Workbench

SQL Server Management Studio (SSMS)

phpMyAdmin

Any compatible SQL interface

Execute the SQL Script

Open the file student_records.sql in your SQL editor.

Execute the script to:

Create the database StudentRecordsDB

Create all necessary tables: Students, Departments, Courses, Instructors, Enrollments, Attendance, Payments, and Exams

Establish primary and foreign key relationships

Verify Tables and Relationships

Check that all tables are created

Confirm that foreign key constraints have been properly applied

🧩 Entity-Relationship Diagram (ERD)

If the image above doesn't load, ensure that your repository includes the image file at ./screenshots/ERD.png.

Alternatively, view the ERD here: [Insert link to online ERD or image viewer if hosted externally]

📂 Repository Contents
student_records.sql – Full SQL script to set up the Student Records database.

README.md – Documentation and setup instructions.

screenshots/ERD.png – Visual representation of the database schema and relationships.

✅ Features
Comprehensive structure for managing student information

Departmental data tied to both courses and instructors

Enrollments and attendance tracking per course

Payment record system for financial tracking

Exam records and score management