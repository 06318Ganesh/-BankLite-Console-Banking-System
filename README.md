# 🏦 BankLite – Console Banking System

**BankLite** is a Python-based mini banking system that simulates core banking operations like creating accounts, depositing and withdrawing funds, viewing balances, and maintaining transaction history. Built using Object-Oriented Programming (OOP), this console application helps users understand the foundational concepts behind real-world banking software.

> 📌 Developed as part of my placement preparation journey with **#placementprep2025** and **#nxtwave**.

---

## 🎯 Objective

To simulate a simple yet realistic banking system where:
- Users can manage their accounts via the console
- All data is stored persistently using a JSON file
- Users can view complete transaction histories

---

## 🧰 Technologies & Concepts Used

| 🔧 Topic                         | ✅ Implemented |
|----------------------------------|----------------|
| Python 3                         | ✅             |
| Object-Oriented Programming (OOP)| ✅             |
| File Handling (JSON)             | ✅             |
| Unique ID Generation (`uuid`)    | ✅             |
| Timestamps (`datetime`)          | ✅             |
| Input Validation                 | ✅             |
| Console-based UI                 | ✅             |

---

## 🚀 Features

- ✅ **Create Account** with unique 8-digit UUID
- 💸 **Deposit & Withdraw** funds with amount checks
- 📊 **View Account Balance** and full **Transaction History**
- 💾 **Save and Load Data** to/from `bank.json`
- 🧾 **Timestamps** for every deposit and withdrawal

---

## 📂 File Structure

BankLite/
│
├── banklite.py # Main source code
├── bank.json # Generated file storing account and transaction data
└── README.md # Project documentation


---

## 💻 How to Run

### 👉 Google Colab (Recommended):
- Open this link: [https://colab.research.google.com/drive/11sj8ihLnC5N2PqzdtY1ILIjPSBriZA38?usp=sharing]
- Run each cell
- Interact with the console interface

### 👉 Local Python:
```bash
python banklite.py
📸 Sample Transaction Output
markdown
Copy
Edit
🏦 BankLite Menu:
1. Create Account
2. Deposit
3. Withdraw
4. View Balance & History
5. Save Data
6. Exit

Enter Account ID: 8a5f2e1b
✅ Deposited ₹500.00
✅ Withdrew ₹250.00

Transaction History:
[2025-07-09 10:00:23] Deposited ₹500.00
[2025-07-09 10:05:45] Withdrew ₹250.00
📘 What I Learned
✅ How to design and implement reusable OOP structures
✅ How to manage real-time data input/output from users
✅ How to persist data using JSON
✅ How real banking systems track and log transactions

💡 Future Enhancements (Optional Ideas)
🔒 Add PIN-based account login system

📈 Interest calculator or recurring deposits

🖥️ GUI version using Tkinter or web version using Flask/Django

🗃️ Database integration with SQLite or MongoDB

📢 Share Your Thoughts
This project helped me grow in both technical and logical thinking. I’d love your feedback, suggestions, or even collaboration ideas!

#placementprep2025 #nxtwave #pythonproject #banking #oop #jsonstorage #filehandling #consoleapp
