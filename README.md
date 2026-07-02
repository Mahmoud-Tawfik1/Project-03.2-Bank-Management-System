# 💳 Bank Management System – Extension 01 (C++)

A console-based extension of the **Bank Management System** built using **C++**.

This version expands the core banking application by introducing a complete **Transactions Menu**, allowing users to perform deposits, withdrawals, and monitor total account balances while preserving all client data through file storage.

The project focuses on extending an existing system using **structured programming**, clean function design, and modular architecture.

---

## 📚 Training Source

This project was developed as part of the training roadmap on:

**Programming Advices Platform**  
Instructor: **Dr. Mohammed Abu-Hadhoud**

🔗 https://programmingadvices.com/

---

## 🎯 Project Objectives

- Extend an existing banking system without modifying its core structure
- Practice **structured programming in C++**
- Implement financial transaction operations
- Reuse existing functions to reduce code duplication
- Improve menu navigation and modular design
- Store updated data permanently using file handling

---

## ✨ New Features

🔹 Dedicated **Transactions Menu**

🔹 Deposit money into client accounts

🔹 Withdraw money with balance validation

🔹 Display all client balances

🔹 Calculate the total balance across all accounts

🔹 Automatic file updates after every transaction

🔹 Confirmation prompts before financial operations

🔹 Seamless integration with the original banking system

---

## 🧠 Concepts Applied

- Structured Programming
- Modular Function Design
- Divide & Conquer
- File Handling (`fstream`)
- Enumerations (`enum`)
- Structures (`struct`)
- Vector-based data management
- Input validation
- Code reusability

---

## 🏦 Transactions Menu

The system now includes a dedicated transactions menu:

- Deposit
- Withdraw
- Total Balances
- Return to Main Menu

Each operation is implemented as an independent function, keeping responsibilities separated and making future extensions easier.

---

## 💾 Data Persistence

Client information continues to be stored in text files.

Every successful deposit or withdrawal immediately updates the stored data, ensuring that no transaction is lost after closing the application.

---

## 🛠 Tech Stack

- **Language:** C++
- **Paradigm:** Structured Programming
- **Application Type:** Console Application
- **Storage:** Text File
- **Libraries Used:**
  - `<iostream>`
  - `<fstream>`
  - `<vector>`
  - `<iomanip>`
  - `<string>`

---

## 🚀 Learning Outcomes

Through this extension I practiced:

- Expanding an existing software project
- Building modular transaction systems
- Reusing functions effectively
- Applying validation for financial operations
- Managing persistent data with file handling
- Maintaining clean and organized code while adding new features
