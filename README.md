# 🐶 Chihuawow Grooming SQL Database

A relational database designed for a fictional dog grooming salon, **Chihuawow Grooming**, to streamline appointment scheduling, customer management, pet records, and business reporting.

Developed as part of **IDS 410 – Database Systems** at the **University of Illinois Chicago**, this project demonstrates database design principles, SQL querying, normalization, and business analytics.

---

## 📌 Project Overview

Managing a pet grooming business involves much more than scheduling appointments. Groomers need to track customer information, pet profiles, grooming services, appointment history, and revenue while ensuring data remains organized and consistent.

This project designs and implements a fully normalized relational database capable of supporting daily operations and providing actionable business insights through SQL.

---

## 🎯 Business Objectives

The database was built to help Chihuawow Grooming:

- Manage customer records
- Store pet information and behavioral notes
- Organize grooming services and pricing
- Schedule appointments
- Track completed, canceled, and no-show appointments
- Monitor revenue
- Analyze customer spending and service demand

---

## 🗂 Database Schema

The database consists of four related tables:

| Table | Purpose |
|--------|---------|
| **Customer_T** | Stores customer contact information |
| **Pet_T** | Stores pet details and links each pet to its owner |
| **Service_T** | Stores grooming services, pricing, and duration |
| **Appointment_T** | Tracks appointments, status, timestamps, and revenue |

### Relationships

- One customer can own multiple pets.
- One pet can have many appointments.
- One grooming service can be performed during many appointments.

This design follows relational database principles using **Primary Keys** and **Foreign Keys** to maintain referential integrity.

---

## 💻 SQL Concepts Demonstrated

- INNER JOINs
- Aggregate Functions
- GROUP BY
- HAVING
- ORDER BY
- TOP
- Subqueries
- UNION Operations
- Business Reporting Queries
- Relational Database Design
- Entity Relationship Diagram (ERD)
- Database Normalization

---

## 📊 Business Questions Answered

The SQL queries answer real business questions, including:

- 🏆 Which customer has spent the most money?
- 💰 What is the total monthly revenue?
- ✂️ Which grooming services are booked most frequently?
- ⭐ Which customers qualify as VIP customers?
- 🐶 Which customers have never scheduled an appointment?
- 📅 How many appointments were completed, canceled, or marked as no-shows?

These queries demonstrate how SQL can transform operational data into meaningful business insights.

---

## 🛠 Technologies Used

- Microsoft Access
- SQL
- Relational Database Design
- Entity Relationship Modeling (ERD)

---

## 📷 Project Documentation

This repository includes:

- Database schema
- Entity Relationship Diagram (ERD)
- Database relationship diagrams
- Sample tables
- SQL query examples
- Final project report

---

## 📚 Skills Demonstrated

- Database Design
- SQL Development
- Relational Modeling
- Data Integrity
- Database Normalization
- Business Analytics
- Problem Solving
- Data Modeling
- Analytical Thinking

---

## 👩‍💻 Author

**Wendy Alpizar**

Information & Decision Sciences • Finance Minor  
University of Illinois Chicago
