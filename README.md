# JDBC Operations Project

## 📌 Description
This project demonstrates basic JDBC operations using MySQL database.

It performs:
- Select employee records
- Update employee details
- Delete employee records

---

## 🛠 Technologies Used
- Java
- JDBC
- MySQL
- MySQL Connector/J

---

## 🗄 Database Setup

```sql
CREATE DATABASE jdbc_db;
USE jdbc_db;

CREATE TABLE employee (
    eId INT PRIMARY KEY,
    ename VARCHAR(50),
    deptId INT
);
