# Data Modeling and Database Persistence 🗄️📊

Welcome to my **Data Modeling and Persistence** repository completed at **Holberton School**. This repository focuses on relational database design, SQL querying, CRUD operations, and complex multi-table joins using relational databases.

---

## 📌 Modules & Core Concepts

| Directory | Description & Concepts | Key SQL Operations |
| :--- | :--- | :--- |
| `sql_crud` | Core database operations (Create, Read, Update, Delete) | `INSERT`, `SELECT`, `UPDATE`, `DELETE`, filtering, sorting |
| `sql_join` | Advanced table relationships and relational querying | `INNER JOIN`, `LEFT JOIN`, `RIGHT JOIN`, `GROUP BY`, aggregates |

---

## 🛠️ Environment & Tools

- **Database Management System (DBMS):** MySQL / PostgreSQL / SQLite
- **Language/Query:** SQL (Structured Query Language)
- **Environment:** Linux / WSL2, Command-line interface

---

## 🚀 How to Execute Queries

To run SQL scripts or test database operations:

```bash
cat sql_crud/0-select_all.sql | mysql -u root -p database_name
# or interactively using sqlite3:
sqlite3 database.db < sql_join/1-inner_join.sql
