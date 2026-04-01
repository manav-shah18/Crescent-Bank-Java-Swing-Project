# Crescent Bank Management System

A robust **Java Swing-based Banking System** integrated with **MySQL**, designed to simulate real-world banking operations such as account management, deposits, withdrawals, and transaction tracking.

---

## Features

* Account Creation
* Deposit & Withdrawal
* Fund Transfer
* Transaction History
* Secure database connectivity using JDBC
* Interactive GUI built with Java Swing

---

## Tech Stack

* **Frontend:** Java Swing (GUI)
* **Backend:** Java
* **Database:** MySQL
* **Connectivity:** JDBC

---

## Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/manav-shah18/Crescent-Bank-Java-Swing-Project.git
cd Crescent-Bank-Java-Swing-Project
```

---

### 2. Setup Database (MySQL)

* Open MySQL Workbench
* Run:

```sql
CREATE DATABASE banking_system;
USE banking_system;
```

* Import the provided `.sql` file

---

### 3. Configure Database Connection

Update credentials in:

```
DatabaseConnection.java
```

```java
String url = "jdbc:mysql://localhost:3306/banking_system";
String user = "root";
String password = "your_password";
```

---

### 4. Run the Project

```bash
javac *.java
java Main
```

OR run using VS Code button

---

## Screenshots

![Home](screenshots/home.png)
![Create Account](screenshots/create.png)
![Transactions](screenshots/transaction.png)

---

## Project Objective

This project demonstrates the implementation of a **desktop-based banking system**, focusing on:

* Database integration using JDBC
* GUI development using Java Swing
* Real-world transaction workflows

---

## Future Improvements

* Add login authentication system
* Improve UI/UX design
* Convert to web-based application (Spring Boot)
* Add encryption for sensitive data

---

## Acknowledgment

Built as part of academic learning and practical implementation of Java and database concepts.
