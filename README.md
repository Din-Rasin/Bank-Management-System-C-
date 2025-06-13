
# 🏦 Bank Management System (C++)

A console-based **Bank Management System built in C++**, designed to perform essential banking operations such as account creation, deposit, withdrawal, balance inquiry, and account deletion.

This project is ideal for learning **Object-Oriented Programming (OOP)** concepts, file handling, and basic system design in C++.

---

## 🚀 Key Features

| Feature                   | Description                                                  |
| ------------------------- | ------------------------------------------------------------ |
| 🧾 **Create Account**     | Collects customer details and generates a new account number |
| 💰 **Deposit**            | Add funds to an existing account                             |
| 💸 **Withdraw**           | Subtract funds with sufficient balance check                 |
| 📋 **Balance Inquiry**    | View account balance and customer info                       |
| 🗑 **Delete Account**     | Remove a customer’s account from the system                  |
| 📝 **Modify Account**     | Edit customer name, address, or contact                      |
| 📂 **Persistent Storage** | File-based storage using C++ file streams (fstream)          |
| 🔐 **Basic Login System** | Optional admin authentication (username/password)            |

---

## 💻 Technologies Used

| Component    | Details                          |
| ------------ | -------------------------------- |
| Language     | C++                              |
| Compiler     | GCC / MinGW / MSVC               |
| File Storage | `.txt` or `.dat` via `fstream`   |
| IDE          | Code::Blocks / VS Code / Dev C++ |

---

## 📂 File Structure

```bash
Bank-Management-System/
├── main.cpp
├── account.h        # Class header for account functions
├── account.cpp      # Account function implementations
├── accounts.dat     # File used to store customer data
└── README.md
```

---

## 🧑‍💻 How It Works

1. **Start Program**: Menu is shown in console
2. **Choose Action**:

   * Create New Account
   * Deposit or Withdraw
   * View all accounts
   * Search account by number
   * Delete or Modify existing accounts
3. **Exit** when complete

---

## 🏁 Sample Menu (UI)

```text
===============================
  BANK MANAGEMENT SYSTEM (C++)
===============================
1. Create Account
2. Deposit Amount
3. Withdraw Amount
4. Balance Inquiry
5. Modify Account
6. Delete Account
7. View All Accounts
0. Exit
===============================
Enter your choice:
```

---

## 🏗 Classes & Functions

### Class: `BankAccount`

```cpp
class BankAccount {
   int accNumber;
   char name[50];
   float balance;

public:
   void createAccount();
   void showAccount() const;
   void deposit(float);
   void withdraw(float);
   int getAccNumber() const;
};
```

---

## 📦 Compilation

### 💡 Using Terminal

```bash
g++ main.cpp -o BankSystem
./BankSystem
```

### 💡 Using Code::Blocks or Visual Studio

* Open the `.cpp` file
* Compile & Run directly

---

## 📸 Screenshot

```text
---------------------------
  Create New Account Menu
---------------------------
Enter Account Number: 1001
Enter Customer Name: John Doe
Enter Initial Deposit: 1500
Account created successfully!
```

---

## 🛠 Improvements You Can Add

* [ ] PIN/password-based login for each account
* [ ] ATM-like interface using ASCII UI
* [ ] Use `.csv` or `.json` instead of `.dat` files
* [ ] GUI version using Qt or C++/CLI
* [ ] Transaction history logging

---

## 📚 Educational Purpose

This project is best suited for:

* Beginners learning C++ OOP
* Students exploring file handling
* Mini-project or semester submission

---

## 📄 License

MIT License – free for use and modification with credit.

---

## 📬 Contact

* GitHub: [Din-Rasin](https://github.com/Din-Rasin)
* Email: denrasin2917@gmial.com

---

