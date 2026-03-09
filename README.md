# JDBC Employee Operations Project

## 📌 Description

This project demonstrates basic JDBC operations using a MySQL database.

It performs:

* Retrieve employee records
* Update employee details
* Delete employee records

---

## 🛠 Technologies Used

* Java
* JDBC
* MySQL
* MySQL Connector/J

---

## 🗄 Database Setup

```sql
CREATE DATABASE db584;
USE db584;

CREATE TABLE employee (
    eId INT PRIMARY KEY,
    ename VARCHAR(50),
    deptId INT
);
```

---

## ▶️ Programs Included

* **Retrieve.java** – Displays all employee records.
* **Update.java** – Updates the department ID of an employee.
* **Delete.java** – Deletes an employee record.

---

## ⚙️ How to Run

```bash
javac Retrieve.java
java Retrieve

javac Update.java
java Update

javac Delete.java
java Delete
```

---

## 🔗 Database Connection

```
URL: jdbc:mysql://localhost:3306/db584
Username: root
Password: 1234
```
