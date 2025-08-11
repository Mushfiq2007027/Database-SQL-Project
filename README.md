# Covid Bed Slot Booking System

## Project Overview

The **Covid Bed Slot Booking System** is a database-driven application designed to efficiently manage hospital bed bookings during the Covid-19 pandemic. It enables hospitals to track beds, patients, staff, and bookings to ensure smooth allocation of ICU and general beds.

This system leverages Oracle SQL and PL/SQL to handle complex data relationships and procedural operations within the database.

---

## Features

- Maintains detailed records of hospitals, patients, staff, beds, and bookings
- Ensures data integrity using primary and foreign key constraints
- Supports data insertion, updating, deletion, and retrieval with filtering options
- Implements advanced SQL operations including joins, set operations (UNION, INTERSECT, MINUS), and aggregate functions
- Uses nested queries, common table expressions (WITH clause), and grouping with HAVING filters
- Provides reusable database logic with views, stored procedures, functions, and triggers
- Demonstrates procedural logic with PL/SQL blocks featuring cursors, loops, conditional branching, and exception handling

---

## Database Schema

The system consists of five core tables:

1. **Hospitals** – Stores hospital details such as ID, name, address, and contact.
2. **Patients** – Contains patient demographics including ID, name, age, contact, and address.
3. **Staff** – Records staff members’ information, their roles, and the hospital they work at.
4. **Beds** – Tracks bed inventory details including bed type, room number, status, and hospital association.
5. **Bookings** – Manages patient bed bookings with start and end dates.

---

## Key Functionalities

- **Data Management:** Insert, update, delete, and view records across all tables.
- **Filtering and Search:** Retrieve data based on conditions like age ranges, roles, bed types, and booking status.
- **Aggregate Insights:** Calculate totals, averages, minimums, and maximums for beds and bookings.
- **Complex Queries:** Use nested subqueries, joins (inner, left/right/full outer), and set operations for advanced data retrieval.
- **Views:** Simplify data access by creating views like AdultPatients or SeniorPatients.
- **PL/SQL Programming:** Incorporate variables, loops, cursors, and conditionals to implement business logic inside the database.
- **Procedures and Functions:** Encapsulate repetitive tasks such as fetching patient details or calculating patient age.
- **Triggers:** Automatically set default values, e.g., bed status on insertion.

---

## PL/SQL Features Demonstrated

- Variable declaration and output using DBMS_OUTPUT
- Cursor usage with row fetching and row counting
- Collection handling with arrays and loops (FOR and WHILE)
- Conditional branching with IF / ELSIF / ELSE statements
- Exception handling with NO_DATA_FOUND
- Creation and execution of stored procedures and functions
- Usage of row types for structured data manipulation

---

## Benefits

- Streamlines bed booking process, helping hospitals manage capacity effectively
- Provides accurate and real-time tracking of bed occupancy and availability
- Facilitates hospital staff management with role assignments and hospital affiliations
- Enhances decision-making through aggregate statistics and detailed reporting
- Enables extensibility with PL/SQL for complex business workflows and automation

---

## Future Work

- Develop a user-friendly web or mobile interface for real-time bed booking and monitoring
- Implement notification systems for patients and staff regarding booking status
- Add role-based access control for secure data handling
- Incorporate analytics dashboards to visualize occupancy trends and resource utilization

---

## Getting Started

To use this project:

1. Set up an Oracle database instance.
2. Create the database schema for Hospitals, Patients, Staff, Beds, and Bookings.
3. Populate tables with initial data.
4. Run PL/SQL blocks, procedures, and functions for data manipulation and retrieval.
5. Execute queries to analyze and report on hospital bed bookings.




