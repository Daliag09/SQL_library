
# 📚 SQL_Library – Library Management System

This project is a simple relational database system for managing a library. It demonstrates the use of SQL for data modeling, integrity constraints, relationships, and basic stored procedures.

## 📌 Description

The system supports the following core functionalities:
- Managing books, authors, categories, and publishers
- Tracking book loans by clients
- Registering library employees
- Creating views for easier reporting
- Implementing procedures for common operations

The database is developed in **Oracle SQL**, using a set of normalized relational tables and appropriate constraints.

---

## 📂 File Structure

The `library_sql.sql` file includes:
- Creation of all tables (`CLIENTUL`, `CARTE`, `AUTOR`, `EDITURA`, `CATEGORIE`, `IMPRUMUT`, `ANGAJAT`, `PUBLICATIE`)
- Insert statements for testing
- Data validation using constraints
- Views for simplified data access
- Stored procedures for reusable logic

---

## 🧰 Technologies Used

- **Oracle SQL / PL-SQL**
- Oracle SQL Developer or any Oracle-compatible environment
- GitLab for versioning and collaboration

---

## 🔧 Installation & Usage

1. Clone the repository:
   ```bash
   git clone https://gitlab.upt.ro/dalia.gogoase/sql_library.git
   cd sql_library
   ```

2. Open `library_sql.txt` in Oracle SQL Developer

3. Execute the script to create and populate the database

---

## 👀 Views

- `VizualizareCarti` – Lists all book titles
- `VizualizareCartiEdituri` – Displays book titles along with their publishers

---

## ⚙️ Procedures

- `AdaugaEditura(...)` – Adds a new publisher
- `afisare_interogari(...)` – Example of dynamic SQL procedure (demo only)

---

## 👤 Author

**Dalia Gogoase**

