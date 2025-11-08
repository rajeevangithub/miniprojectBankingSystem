# 🏦 Bank Management System (Python + SQLite)

A simple **command-line based Bank Management System** built using **Python** and **SQLite3**.  
It allows users to **register**, **login**, **deposit**, **withdraw**, and **view transaction history**.  
The project demonstrates core database operations and control flow in Python.

---

## 📋 Features

- 👤 User Registration & Login  
- 💰 Deposit & Withdraw Funds  
- 📜 Transaction History (All, Deposit, Withdraw filters)  
- 🧾 Automatic Account Creation (Savings)  
- 🔐 Password Validation  
- 🗃 SQLite Database Integration  
- 🧠 Simple CLI Menu Interface  

---

## 🏗 Database Schema

| Table | Fields |
|--------|---------|
| **users** | id, first_name, last_name, role, email, phone, password |
| **accounts** | id, user_id, balance, account_no, type, status, created_at |
| **transactions** | id, user_id, account_id, amount, date, type |

---

## ⚙️ Requirements

- Python 3.8 or higher  
- SQLite3 (built-in with Python)
- Modules:
  - `sqlite3`
  - `datetime`
  - `random`

Optional (for documentation generation):
- `reportlab`

---

## 🚀 How to Run

1. **Clone or Download** the repository:
   ```bash
   git clone https://github.com/your-username/bank-management-system.git
   cd bank-management-system
