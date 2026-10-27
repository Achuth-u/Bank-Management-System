
# 🏦 Bank Management System

## 📌 Project Overview

The **Bank Management System** is a Python-based application that allows users to create bank accounts, log in securely, check their account balance, deposit money, withdraw money, and view transaction history.

The system uses an Excel file (`bank.xlsx`) as its database to store account details and transaction records. It also uses SHA-256 hashing to store passwords as hashes instead of plain-text passwords.

This project demonstrates Python programming, file handling, data management, password hashing, and basic banking operations.

## 🎯 Objectives

- Create and manage bank accounts.
- Provide account login with password verification.
- Store account details in an Excel workbook.
- Check the current account balance.
- Deposit and withdraw money.
- Maintain transaction history.
- Store passwords using SHA-256 hashing.
- Generate unique six-digit account numbers.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| OpenPyXL | Read and write Excel files |
| Excel (.xlsx) | Store account and transaction data |
| Hashlib | Password hashing |
| Random | Generate account and transaction IDs |
| Datetime | Record transaction date and time |
| OS | Check whether the database file exists |

## ✨ Features

### 1. Create Account
- Enter name, age, phone number, and password.
- Automatically generate a six-digit account number.
- Store account information in `bank.xlsx`.
- Initialize the account balance to zero.

### 2. Login System
- Log in using the account number and password.
- Verify the entered password against the stored password hash.
- Allow access to banking operations after successful authentication.

### 3. Check Balance
- Display the current account balance.

### 4. Deposit Money
- Enter the amount to deposit.
- Validate that the amount is greater than zero.
- Update the account balance.
- Record the transaction details.

### 5. Withdraw Money
- Enter the withdrawal amount.
- Validate the amount.
- Prevent withdrawals exceeding the available balance.
- Update the balance and save the transaction.

### 6. Transaction History
- Display the account's transaction records.
- Show transaction ID, transaction type, amount, updated balance, and date.

### 7. Logout and Exit
- Log out of the current account.
- Exit the application.

## 📂 Project Structure

```text
Bank-Management-System/
│
├── bank.py
├── bank.xlsx
└── README.md
```

**Note:** `bank.py` is the Python source file. The program automatically creates `bank.xlsx` when it is first run if the file does not exist.

## ⚙️ Installation and Setup

### Prerequisites

- Python 3.10 or later
- pip package manager

### Step 1: Clone the Repository

```bash
git clone https://github.com/Achuth-u/Bank-Management-System.git
```

### Step 2: Navigate to the Project Folder

```bash
cd Bank-Management-System
```

### Step 3: Create a Virtual Environment (Optional)

```bash
python -m venv venv
```

Activate the environment on Windows:

```bash
venv\Scripts\activate
```

### Step 4: Install Dependencies

```bash
pip install openpyxl
```

The `os`, `hashlib`, `random`, and `datetime` modules are included with Python.

### Step 5: Run the Application

```bash
python bank.py
```

## 🗄️ Database Structure

The application creates an Excel workbook named `bank.xlsx` with two worksheets.

### Accounts Sheet

| Column | Description |
|---|---|
| Account No | Unique six-digit account number |
| Name | Account holder's name |
| Age | Account holder's age |
| Phone | Contact number |
| Password Hash | SHA-256 hash of the password |
| Balance | Current account balance |

### Transactions Sheet

| Column | Description |
|---|---|
| Transaction ID | Transaction reference |
| Account No | Account associated with the transaction |
| Type | Deposit or Withdrawal |
| Amount | Transaction amount |
| Balance | Balance after the transaction |
| Date | Transaction date and time |

## 🔄 Application Workflow

1. Start the application.
2. Create a new account or log in to an existing account.
3. After login, select an operation from the banking menu.
4. Perform balance checks, deposits, withdrawals, or transaction history checks.
5. The application updates the Excel workbook after successful transactions.
6. Log out or exit the application.

## 🔐 Security Considerations

- Passwords are stored as SHA-256 hashes rather than plain text.
- Users must log in before accessing account operations.
- Withdrawals are restricted when the available balance is insufficient.
- Invalid or non-positive transaction amounts are rejected.

**Important:** This is an educational project, not production-ready banking software. SHA-256 without a password-specific salt and a password-hashing algorithm such as Argon2 or bcrypt is not sufficient for real banking security. An Excel workbook is also not suitable as a secure, concurrent banking database.

## 🚀 Future Enhancements

- Add input validation for age, phone number, and account number.
- Use salted password hashing with Argon2 or bcrypt.
- Replace Excel storage with SQLite, MySQL, or PostgreSQL.
- Add account details and profile management.
- Generate downloadable transaction statements.
- Add unique transaction ID generation with collision checks.
- Build a graphical user interface using Tkinter or PySide6.
- Add administrative functions and account management.
- Implement automated tests and improved error handling.

## 🎓 Learning Outcomes

Through this project, you can learn:

- Python functions and control flow.
- File handling with OpenPyXL.
- Working with Excel worksheets and rows.
- Password hashing using `hashlib`.
- Random number generation.
- Date and time handling.
- Input validation and conditional logic.
- Basic account and transaction management.

## 👨‍💻 Author

**ACHUTH U**

GitHub: [https://github.com/Achuth-u)

## 📜 License

This project is intended for educational and learning purposes. You may add an MIT License if you want to distribute it as an open-source project.
