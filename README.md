# 🔐 Coffee Shop Database System

## 📌 Project Overview
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
