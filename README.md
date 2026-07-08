# Database Project: GAL Exam Management

Repository containing the documentation and implementation of the database project for the **Database Systems** course.

## Project Objective
The project consists of the conceptual design, logical design, and physical implementation (via DDL and DML instructions) of a relational database dedicated to managing university exam sessions. The "Geometry and Linear Algebra" (GAL) exam was analyzed as the primary application domain and case study.

The system is structured to model two macro-areas:
* **Logistics:** Classroom management, shift assignment based on alphabetical ranges, maximum capacity enforcement, classroom eligibility verification for students with SLD (Specific Learning Disabilities / DSA) certifications, and the assignment of academic and non-academic staff for exam invigilation and grading.
* **Evaluation:** Tracking of individual tests (midterms or comprehensive exams), calculation of technical grades, management of final outcomes (including potential oral integrations), tracking of official registration status, and enforcement of academic barriers (e.g., pending OFA / Additional Educational Obligations).

## Technologies Used
* **DBMS:** PostgreSQL. Selected for its strict adherence to ANSI SQL standards and its efficient management of domain and referential integrity constraints.
* **Database Design:** Entity-Relationship (E-R) model for the conceptual schema; Relational Model for the logical schema.
* **Documentation:** HTML and CSS. A static web interface was developed to facilitate easy navigation through the schemas, architectural choices, and SQL query execution results.

## Project Documentation
The complete technical documentation, high-resolution schemas, and the output of SQL queries and views are available on the following interactive web page:

https://mlaklaa.github.io/Progetto_Database_GAL/

## Project Team
Project developed for the June 2026 academic session by:
* Laklaa Marwa (Student ID: 1099064)
* Frimane Karima
* Derouich Sukaina
