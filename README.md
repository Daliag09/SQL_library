
# 📚 SQL_Library – Library Management System (Bachelor’s Thesis)

This project is a relational database system designed to manage a library, developed as part of a bachelor's thesis.

## 📌 Description

The system supports the following core functionalities:
- Management of books, authors, categories, and publishers
- Tracking book loans to clients
- Managing library employees
- Views and stored procedures for frequent queries

The project is written in **SQL** for **Oracle Database** and includes relational tables, constraints, data insertion, **views**, **stored procedures**, and validations.

---

## 📂 File Structure

The `licenta_baza_date.sql` file contains:
- Creation of all tables (`CLIENTUL`, `CARTE`, `AUTOR`, `EDITURA`, `CATEGORIE`, `IMPRUMUT`, `ANGAJAT`, `PUBLICATIE`)
- Data insertions to populate them
- Constraints to ensure data integrity
- Views for simplified reporting
- Procedures for automated operations

---

## 🧰 Technologies Used

- **Oracle SQL / PL-SQL**
- Oracle SQL Developer or any Oracle-compatible environment
- GitLab for version control and collaboration

---

## 🔧 Installation & Usage

1. Clone the repository:
   ```bash
   git clone https://gitlab.upt.ro/dalia.gogoase/licenta_gogoase_dalia.git
   cd licenta_gogoase_dalia
   ```

2. Open the `licenta_baza_date.sql` file in an Oracle environment (e.g., Oracle SQL Developer)

3. Run the script to create the database and populate it with test data

---

## 👀 Useful Views

- `VizualizareCarti` – displays the names of all books
- `VizualizareCartiEdituri` – shows a list of books and their corresponding publishers

---

## 📌 Stored Procedures

- `AdaugaEditura(...)` – adds a new publisher to the database
- `afisare_interogari(...)` – sample procedure using dynamic SQL (educational demo)

---

## ✍️ Author

**Dalia Gogoase**  
Faculty of Automation and Computing – Politehnica University of Timișoara  
Class of 2025

---

## 📜 License

This project was created for educational purposes. All rights reserved by the author.  
Distribution is only allowed with explicit permission.

---

## ✅ Project Status

📅 Completed – All functional components have been implemented and tested.
