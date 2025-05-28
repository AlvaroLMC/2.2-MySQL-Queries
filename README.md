# 🛠️ Database Query Exercises - MySQL

## 📄 Description

This project includes a series of practical exercises to work with SQL queries on two different databases: **Store** and **University**. Each exercise is designed to work with well-structured data using tools like `JOIN`, conditions, aggregations, and other advanced SQL concepts.

### 🧩 Proposed Exercises

#### Database: Store
- The database includes two tables: `product` and `manufacturer`.
- The goal is to perform queries such as filtering, sorting, data conversions, and relationships between tables.

#### Database: University
- This database includes tables related to `students`, `teachers`, `departments`, `degrees`, and `subjects`.
- The aim is to work with complex operations such as relational hierarchies, outer joins (`LEFT JOIN`, `RIGHT JOIN`), and summary queries.

Each exercise is designed to practice essential SQL concepts, from basic to more advanced operations.

---

## 💻 Technologies Used

This project uses only database-related technologies and tools. Here's a list of what's used:

- **MySQL** version 8.0 or higher.
- SQL scripts for data definition and manipulation (DDL, DML).
- Editing and connection tools:
  - MySQL Workbench
  - DBeaver or Navicat *(optional)*
  - MySQL command-line interface
- Text editor for reviewing and editing scripts (e.g., Visual Studio Code).

---

## 📋 Requirements

Before getting started, make sure you meet the following minimum requirements:

- MySQL database installed on your system (version 8.0 or higher recommended).
- A GUI tool (Workbench, DBeaver, etc.) to load and run SQL scripts.
- Internet access to download the scripts from this repository.
- [Optional] A local database server such as **XAMPP** or **WAMP**.

---

## 🛠️ Installation

Follow the steps below to set up the environment and load the databases:

### 1. Clone the repository

      ```bash
      git clone https://github.com/AlvaroLMC/2.2-MySQL-Queries.git
      cd 2.2-MySQL-Queries

2. Configure your MySQL server

Start your local MySQL server (using XAMPP, WAMP, or any other MySQL server).

Make sure you know your username (root) and password (by default, root has no password).
3. Load the database schemas

  - To load the Store database:
      ```bash
    mysql -u root -p < schema_tienda.sql

  - To load the University database:
      ```bash
    mysql -u root -p < schema_universidad.sql

▶️ Execution

Once the database schemas are loaded, you can start executing the proposed queries:

1. Open your preferred SQL tool (e.g., MySQL Workbench or DBeaver).

2. Select the corresponding database with one of the following commands:
      ```bash
    USE tienda;
    USE universidad;

3. Load and execute the queries provided in the following files:

   - consultas_tienda.sql → Exercises for the Store database.

   - consultas_universidad.sql → Exercises for the University database.

4. Review the results in your tool.

   - Each query is designed to return a specific output based on the provided tables.
