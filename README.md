# Student-Records
# University Database Management System

This project is a simple **University Database Management System** built using **Python** and **MySQL**. It allows users to interact with a university database through a command-line menu.

## Project Files

- `university.py` — Python program used to connect to the database and perform operations.
- `university3.sql` — SQL file used to create and populate the university database.

## Features

The Python program allows users to:

- View all courses
- View all departments
- Enroll a student in a course section
- View faculty teaching schedules
- View students enrolled in a section
- View student information
- Search for courses by name
- Update student major details
- View all course sections

## Database Structure

The database is named `university` and includes the following tables:

- `college`
- `department`
- `course`
- `faculty`
- `section`
- `student`
- `studies_in`
- `offers`
- `works_for`

The database uses primary keys and foreign keys to connect colleges, departments, courses, faculty, students, and course sections.

## Technologies Used

- Python
- MySQL / MariaDB
- MySQL Connector for Python
- phpMyAdmin

## How to Run the Project

### 1. Import the Database

Open phpMyAdmin or MySQL and import the file:

```sql
university3.sql
