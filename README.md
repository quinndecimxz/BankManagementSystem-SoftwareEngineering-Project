# Bank Management System (BMS)

A multi-user, role-based web application designed to automate and centralize core banking operations.

This system was developed as a Software Engineering project to simulate real-world commercial banking processes including customer management, account handling, transaction processing, loan management, employee administration, and daily financial reporting.

---

## 📌 Project Overview

Traditional banking operations relying on manual or fragmented systems lead to:

- Data inconsistencies
- Security vulnerabilities
- Operational delays
- Lack of centralized reporting

This project provides a centralized Bank Management System to address these challenges using a secure, scalable, and modular architecture.

---

## 🏗 System Architecture

- Web-Based Application
- Multi-User Environment
- Role-Based Access Control (RBAC)
- Modular Design for Scalability & Maintainability

---

## 👥 Core Modules

### 1️⃣ Customer Management
- Customer registration and profile management
- Storage of personal details (Customer ID, CNIC, contact, address)
- Multiple accounts per customer
- Account status control (Active, Frozen, Closed)

### 2️⃣ Account Management
- Account opening and closing
- Support for Savings, Current, and Fixed Deposit accounts
- Unique account number generation
- Account status tracking
- Transaction history viewing

### 3️⃣ Transaction Management
- Credit (Deposit) processing
- Debit (Withdrawal) processing
- Fund transfers
- Transaction validation
- Automatic balance calculation
- Transaction logging

### 4️⃣ Loan Management
- Loan application submission
- Loan approval/rejection workflow
- Interest rate and duration tracking
- Repayment monitoring
- Outstanding balance calculation

### 5️⃣ Employee Management
- Employee record management
- Attendance tracking
- Salary management (basic pay, overtime, bonuses)
- Role assignment for access control

### 6️⃣ Authorization & Access Control
- Secure authentication
- Role-Based Access Control (Admin, Manager, Teller, Loan Officer)
- Restricted access to sensitive operations
- Audit trail logging

### 7️⃣ Reporting & Daily Operations
- Daily transaction reports
- Total credit/debit summaries
- Loan disbursement and repayment reports
- Financial performance tracking

---

## 📋 Functional Requirements

The system supports:

- Customer registration and updates
- Account creation and management
- Secure credit/debit transactions
- Fund transfers with validation
- Loan approval workflows
- Transaction history tracking
- Report generation
- Role-based feature access

---

## 🔐 Non-Functional Requirements

### Security
- Encrypted sensitive data
- Secure password hashing
- Audit logging for financial activities

### Performance
- Response time under 3 seconds (normal load)
- Multi-user concurrency support

### Reliability
- Data consistency during concurrent transactions
- 99% availability during business hours

### Usability
- User-friendly interface
- Minimal training required

### Maintainability
- Modular system design
- Easy bug fixing and enhancements

### Scalability
- Supports growth in customers, accounts, and transactions

---

## 🧠 Domain Model – Core Entities

- Customer
- Account
- Transaction
- Loan
- Employee
- Role
- Branch
- Report
- AuditLog

---

## 🔄 Use Case Highlight

**Use Case: Manage Customer Banking Transactions**

Primary Actor: Bank Teller

The system enables secure processing of deposits, withdrawals, and fund transfers while validating:

- Account status
- Sufficient balance
- Destination account integrity

All successful transactions are logged, balances are updated, and receipts are generated automatically.

---

## 🎯 Project Goals

- Centralize banking operations
- Improve operational efficiency
- Reduce manual errors
- Strengthen security
- Provide scalable infrastructure for future growth

---

## 👨‍💻 Team Members

- Zain Ali — BITF24A021  
- Abdul Ahad Latif — BITF24A007  

---

## 📚 Academic Context

Course: Software Engineering  
Submitted to: Sir Anzar (Assistant Professor)

---

This project demonstrates applied software engineering principles including requirement engineering, system modeling, access control design, and modular architecture implementation.
