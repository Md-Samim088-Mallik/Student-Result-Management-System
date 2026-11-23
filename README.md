# Student Result Management System (MySQL)

## About the Project

The Student Result Management System is a SQL-based database project designed to manage student academic records and examination results.

It maintains student details, class information, subjects, examinations, and marks in a structured relational database. It also uses SQL queries, views, and triggers to analyse student performance and generate result reports.

## Project Objectives

- Manage student and class information.
- Store subject-wise examination marks.
- Automatically generate grades.
- Validate marks before inserting records.
- Identify class toppers.
- Analyse subject-wise performance.
- Generate student report cards.

## Database Tables

| Table | Purpose |
|---|---|
| Classes | Class and section details |
| Students | Student information |
| Subjects | Subject information |
| Exams | Examination details |
| Marks | Student examination marks |

## Main SQL Operations

**1. Database Creation**

Created a relational database with primary keys, foreign keys, unique constraints, and check constraints.

**2. Data Management**

Used INSERT and SELECT statements to store and retrieve student records.

**3. Data Analysis**

Used JOIN, GROUP BY, ORDER BY, and aggregate functions to analyse academic performance.

**4. Automatic Grade Generation**

Implemented SQL triggers to assign grades based on marks obtained.

**5. Marks Validation**

Implemented a trigger to prevent invalid marks from being inserted.

**6. Views and Reports**

Created SQL views to generate student result summaries and report cards.

**7. Transaction Management**

Demonstrated transaction operations using START TRANSACTION, COMMIT, and ROLLBACK.

## Technologies

- MySQL
- SQL
- MySQL Workbench

## How to Execute

1. Download or clone this repository.
2. Open MySQL Workbench.
3. Open `student_result_management.sql`.
4. Execute the SQL script.
5. Explore the database tables and execute the reporting queries.

## Expected Outputs

- Student details
- Class-wise student records
- Subject-wise marks analysis
- Student total marks and percentage
- Automatic grade assignment
- Academic performance reports

## Learning Outcomes

Through this project, I practised relational database design, SQL query writing, joins, aggregate functions, triggers, views, and transaction management.

---

**Project:** Student Result Management System  
**Database:** MySQL  
**Project Level:** Beginner to Intermediate
