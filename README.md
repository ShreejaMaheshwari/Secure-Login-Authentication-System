
# 🔐 Secure Login & User Authentication System

A Java + MySQL project that implements secure user authentication using **salted SHA-256 password hashing** and JDBC.

## 🚀 Tech Stack
- Java 17
- MySQL 8+
- JDBC
- Maven

## 🧠 Features
- Secure user registration and login
- Salt + SHA-256 password hashing
- Role-based accounts (User/Admin ready)
- MySQL integration via JDBC
- Fully modular Maven project

## ⚙️ Setup
1. Clone or download this repository.
2. Import as **Maven Project** in IntelliJ or Eclipse.
3. Run the SQL script from `src/main/resources/secure_auth.sql` in MySQL Workbench.
4. Update DB credentials in `DBConnection.java`.
5. Build & Run:
   ```bash
   mvn clean compile exec:java

