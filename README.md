IRCTC Railway Reservation System (Backend)
A simplified command-line-based railway reservation system simulating IRCTC's core functionalities, built using Java, OOPs principles, and MySQL.

Features

✅ User Authentication – Register, login, and manage user profiles.
✅ Train Search & Booking – View available trains, check seats, and book tickets.
✅ Ticket Management – View/Cancel bookings, and generate PNR receipts.
✅ Admin Panel – Add/update trains, routes, and manage schedules (MySQL-backed).

Tech Stack

Core Java (OOPs, Collections, Exception Handling)
MySQL (Database for users, trains, bookings)
JDBC (Java-Database Connectivity)
Database Schema

Tables: users, trains, bookings, stations, etc.
Designed with normalized relations to avoid redundancy.
How to Run?

Prerequisites:
Java 8+
MySQL Server (Configure db.properties with your credentials).
Setup DB: Run the SQL_Setup.sql script to create tables.
Run: Execute Main.java to start the application.
