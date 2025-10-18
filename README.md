# 🍽️ Restaurant Reservation System

A SQL-based project designed to manage and automate the process of restaurant reservations.  
This database system handles reservations, customers, tables, and staff details efficiently using structured queries and stored procedures.

---

## 📘 Project Overview
This project implements a complete **Restaurant Reservation System** using SQL scripts.  
It covers database design, data population, and example queries to demonstrate typical operations like adding reservations, managing customers, and viewing available tables.

The system aims to simplify the management of restaurant operations by providing a structured and scalable database foundation.

---

## 🗂️ Project Files

| File | Description |
|------|--------------|
| **Creation.sql** | Creates the database schema — including all tables, keys, and relationships. |
| **DataPopulation.sql** | Populates the database with initial sample data (customers, tables, reservations, staff, etc.). |
| **Queries and Procedures.sql** | Contains SQL queries and stored procedures for performing and automating common tasks. |

---

## ⚙️ How to Run

### 1. Create the Database
Run the `Creation.sql` script to generate all necessary tables and relationships.
```sql
-- Step 1
SOURCE Creation.sql;
```

### 2. Populate the Data
Insert test data using the `DataPopulation.sql` script.
```sql
-- Step 2
SOURCE DataPopulation.sql;
```

### 3. Execute Queries and Procedures
Use the `Queries and Procedures.sql` file to test queries and stored procedures.
```sql
-- Step 3
SOURCE "Queries and Procedures.sql";
```

💡 *Make sure to execute the scripts in this exact order to avoid dependency errors.*

---

## 🧩 Features
- ✅ Structured schema for restaurants, tables, customers, and reservations  
- ✅ Preloaded test data for quick setup and testing  
- ✅ Custom queries and stored procedures for real-world scenarios  
- ✅ Easy to modify and extend for larger systems or applications  

---

## 🧠 Technologies Used
- **SQL / MySQL**
- **Stored Procedures**
- **Relational Database Design**

---

## 🧱 Database Diagram (ERD)
<img width="851" height="682" alt="image" src="https://github.com/user-attachments/assets/7edf259b-b00c-4456-bb5c-2f707dd70cd7" />
