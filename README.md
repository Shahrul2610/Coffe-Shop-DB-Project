
# ☕ Coffee Shop Database System & Analytics

## 📌 Project Overview
This project demonstrates the design and implementation of a **relational database system** for a retail coffee shop.  
It covers **database modeling, SQL schema design, data insertion, analytics queries, indexing, and transaction handling (ACID)**.

The project is built to reflect **real-world business scenarios** and follows **industry standards commonly expected in database-related interviews in Malaysia**.

---

## 🎯 Objectives
- Design a **normalized relational database (3NF)**
- Implement **SQL schema with constraints**
- Perform **business analytics using SQL**
- Demonstrate **transaction management and ACID principles**
- Apply **query optimization using indexes**

---

## 🛠️ Tools & Technologies
- Database: **MySQL / PostgreSQL**
- Language: **SQL**
- Concepts:
  - Relational Database Design
  - Normalization (1NF – 3NF)
  - Joins & Aggregations
  - Indexing & Optimization
  - Transactions & ACID

---

## 🗂️ Database Structure

### 📊 Tables
- **Customers** – Stores customer information
- **Products** – Stores product details
- **Orders** – Stores customer orders
- **Order_Items** – Stores items per order
- **Payments** *(optional extension)*

### 🔗 Relationships
- One customer → many orders
- One order → many order items
- One product → many order items

📌 The design avoids data duplication and follows **Third Normal Form (3NF)**.

---

## 🧱 Schema Design
All table creation scripts are located in:

This project demonstrates a **secure, production-ready relational database system** for a coffee shop business.

It focuses not only on database design, but also on:
- Security
- User authorization
- Transaction integrity
- Automation
- Data retention

The project reflects **real-world database operations** commonly expected in **DBA, Data Engineer, and Backend roles in Malaysia**.

---

## 🎯 Key Features
- Normalized relational database (3NF)
- Role-Based Access Control (RBAC)
- Data masking for sensitive information
- Transaction management (ACID)
- Audit logging using triggers
- Automated backup and reporting
- Data retention policy

---

## 🛠️ Technologies
- MySQL / PostgreSQL
- SQL
- Linux (cron jobs)

---

## 🧱 Database Entities
- Users
- Customers
- Products
- Orders
- Order_Items
- Audit_Log

---

## 🔐 Security & Authorization
- Different roles: cashier, manager, admin
- Principle of least privilege
- Masked views for sensitive customer data
- No direct access to raw PII for non-admin users

---

## 🔁 Transactions & ACID
Transactions are implemented to ensure:
- Atomicity: All operations succeed or fail together
- Consistency: Database rules are always enforced
- Isolation: Concurrent transactions do not conflict
- Durability: Committed data persists after system failure

---

## 📝 Audit Logging
All critical operations are logged using database triggers.
This enables:
- Activity tracking
- Fraud detection
- Compliance reporting

---

## ⏰ Automation
- Daily database backup using cron
- Automated sales reporting
- Scheduled data cleanup tasks

---

## 🧹 Data Retention
Audit logs older than one year are automatically removed
to prevent uncontrolled database growth and ensure compliance.

---

## 📂 Project Structure
