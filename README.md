# STUDENT-COURSE-ENROLLMENT-SYSTEM---MINI-PROJECT
A MySQL-based student course enrollment system demonstrating relational database design, data integrity, and advanced SQL queries for academic data analysis.

#  Student Course Enrollment System (MySQL)

##  Overview

This project is a structured relational database system built using MySQL to manage student enrollments, courses, exams, and performance analytics.
It emphasizes **scalable database design, data integrity, and analytical querying**, simulating a real-world academic management system.


##  Objectives

* Design a normalized relational database
* Implement real-world entity relationships
* Ensure data consistency using constraints
* Perform analytical queries to extract insights


##  Core Concepts Demonstrated

* Database Normalization (1NF, 2NF, 3NF)
* Primary & Foreign Key Constraints
* Many-to-Many Relationship Handling
* JOIN Operations (INNER, LEFT)
* Aggregations (COUNT, AVG)
* Subqueries & Nested Queries
* Conditional Logic using CASE


##  System Architecture

###  Entities:

* Students
* Courses
* Enrollment
* Exams
* Results

###  Relationships:

* Students ↔ Courses → Many-to-Many (via Enrollment)
* Students → Exams → Results → One-to-Many

##  Tech Stack

* MySQL
* MySQL Workbench


##  Key Functionalities

###  Student Management

* Store and manage student data

###  Course Management

* Maintain course details with credits

###  Enrollment Tracking

* Handle many-to-many relationships efficiently

###  Exam & Result Processing

* Record exam attempts and performance


##  Analytical Queries Implemented

* ✔ Students enrolled in specific courses
* ✔ Course-wise enrollment count
* ✔ Highest scoring student
* ✔ Students not enrolled in any course
* ✔ Courses with no exams conducted
* ✔ Average marks per course
* ✔ Grade-based filtering (A, B, C)
* ✔ Month-wise exam analysis
* ✔ Student with maximum enrollments

##  Sample Insights

* Identified **top-performing students** using sorting & limiting
* Detected **missing relationships** using LEFT JOIN
* Generated **course-wise performance metrics**
* Implemented **dynamic grading logic** using CASE



##  How to Execute

1. Open MySQL Workbench
2. Run `Student_Assignment_mini_project.sql` to create database & tables
3. Execute `insert_data.sql` to populate data
4. Run queries from `queries.sql`



## 👩‍💻 Author

** POOJA GOUDA **


