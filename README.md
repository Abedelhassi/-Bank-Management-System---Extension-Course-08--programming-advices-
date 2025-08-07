# 🏦 Bank Management System - Extension (Course 08)

This project is an advanced version of the Bank Management System built during Course 07 in the roadmap by [Mohammed Abu Hadhoud](https://www.youtube.com/@MohammedAbuHadhoud).

In this extension, we added multiple features such as:

- 🔐 User authentication and permissions system
- 💳 Deposit & Withdraw functionality
- 📊 Display total balances
- 👤 Manage users (add/update/delete/search)
- 📁 File-based data storage using text files
- 📌 Enhanced modular design using structs, enums, and functions

---

## 💡 Course Context

> 📚 Course Name: Algorithms and Problem Solving - Level 4  
> 🧠 Main Focus: File management, user systems, bank transactions, permission logic, input validation  
> 🧑‍🎓 By: Mohammed Abu Hadhoud  
> 🗂️ This project is a follow-up to the [Bank Management System - Level 3](../07-Bank-System).

---

## ⚙️ Features

- 🧑‍💼 Multi-user login system with custom permissions (admin, limited access...)
- 🧾 Client CRUD operations: Add, View, Update, Delete, Search
- 💰 Transactions: Deposit and Withdraw
- 📂 File persistence: All data saved in .txt files (Clients.txt, Users.txt)
- 🔐 Permissions-based access control

---

## 📦 File Structure

`bash
📁 Bank-System-Extension
├── main.cpp
├── Clients.txt
├── Users.txt
└── README.md


---

🔑 Permissions Model

Each user can have specific permissions assigned using a bitmask:

Permission Value

List Clients 1
Add New Client 2
Delete Client 4
Update Client 8
Find Client 16
Transactions 32
Manage Users 64
Full Access -1



---

🧑‍💻 Author

> Abed-El-Hassib Lakhdari
🎓 Computer Science Student
💡 Passionate about problem solving and building real-world applications in C++




---

📜 License

This project is part of a self-learning path. Feel free to use it for educational purposes.


---

🌟 Give it a ⭐️ if you found it helpful or inspiring.

---
