# 🏦 Banking Management System - Group Project

![License](https://img.shields.io/badge/license-MIT-blue.svg)  
A secure and user-friendly web application for bank administration and account management.

---

## 📌 Project Overview

The **Banking Management System** is designed to streamline internal bank operations such as account handling, secure transactions, administrative management, and real-time dashboard insights. This system empowers bank staff with responsive and secure interfaces tailored for both clients and admins.

---

## ✨ Features

- 🔐 Secure Admin & Client Login
- 🏦 Account Overview with Balance Info
- 💸 Transaction Processing (Deposit, Withdraw, Transfer)
- 📊 Real-Time Admin Dashboard
- 🔔 Announcements Module
- 📁 File Upload Support (Client Proofs/Docs)
- ⚙️ Role-Based Access Control
- 📈 System Analytics (Total Accounts, Activities, Balances)

---

## 🛠️ Technologies Used

- **Frontend**: HTML5, CSS3, JavaScript, Bootstrap 4
- **Backend**: PHP 7.x
- **Database**: MySQL (XAMPP)
- **UI Framework**: AdminLTE
- **Security**: Session Handling, Password Hashing, Input Validation

---

## 🖥️ Screenshots

Login Page  
![Login](screenshots/login.png)

Client Dashboard  
![Client Dashboard](screenshots/client_dashboard.png)

Admin Panel  
![Admin Dashboard](screenshots/admin_dashboard.png)

---

## 🚀 Getting Started

1. Clone this repository:
   ```
   git clone https://github.com/yourteam/banking-management.git
   ```

2. Import the database from `/database/banking.sql` into your MySQL server.

3. Configure `/config.php` with your DB credentials:
   ```php
   define('DB_SERVER', 'localhost');
   define('DB_USERNAME', 'root');
   define('DB_PASSWORD', '');
   define('DB_DATABASE', 'banking');
   ```

4. Start Apache & MySQL from XAMPP. Navigate to:
   ```
   http://localhost/banking/
   ```



© 2025 Group-1: Coding Frontiers
