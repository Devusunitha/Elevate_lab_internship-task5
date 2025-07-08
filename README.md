# Elevate Lab SQL Internship – Task 5  
## College Event Management System – SQL Joins

This task is part of the Elevate Lab SQL Developer Internship and focuses on combining data from multiple related tables using various types of SQL joins. The goal is to understand and apply different join operations to extract meaningful combined data from normalized relational structures.

---

## Objective

To demonstrate the ability to merge and relate data across tables using SQL joins such as `INNER JOIN`, `LEFT JOIN`, `RIGHT JOIN`, and `FULL OUTER JOIN`. This task uses real-world entities from a college event management system to showcase practical join usage.

---

## Database Used

**Database Name:** `CollegeEventDB`  
This schema models the backend for a college fest and includes modules such as student registrations, team formation, event scheduling, venue management, participation tracking, and result declarations.

---

## Tables Involved

- `Student`  
- `Team`  
- `Event`  
- `Venue`  
- `Participation`  
- `Result`

---

## Tasks Performed

- Used `INNER JOIN` to retrieve data present in both joined tables (e.g., events with venue details).
- Applied `LEFT JOIN` to show all records from one table and matching records from the second (e.g., students and the teams they lead).
- Simulated `RIGHT JOIN` using reversed `LEFT JOIN`, since standard MySQL may not support it.
- Emulated `FULL OUTER JOIN` by combining `LEFT JOIN` and `RIGHT JOIN` using `UNION`.
- Joined three or more tables to fetch combined information across multiple relationships.
- Demonstrated how joins can be used to correlate events, results, teams, and students.

---

## Concepts Demonstrated

- `INNER JOIN`: Retrieves matching records from both tables.  
- `LEFT JOIN`: Returns all records from the left table and matching records from the right.  
- `RIGHT JOIN`: Returns all records from the right table and matching from the left (emulated in MySQL).  
- `FULL OUTER JOIN`: Includes all records from both tables, with `NULL` where no match exists (emulated using `UNION`).  
- Multi-table joins: Joining more than two tables to combine information across layers.  
- Joins involving foreign key relationships and condition-based logic.

---

## Execution Instructions

1. Ensure the `CollegeEventDB` database and relevant tables are created and populated.
2. Open the `task5.sql` script in MySQL Workbench or your SQL tool.
3. Run each query and verify the output for correctness and join behavior.

---
