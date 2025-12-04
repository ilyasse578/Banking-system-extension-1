# Banking System Extension 1 💳🏦

A simple **C++ console-based banking system** that allows managing clients and performing transactions. Built as a practice project to demonstrate file handling, data structures, and menu-driven programming in C++.

---

## Features ✨

- **Client Management**
  - Add new clients with account number, pin code, name, phone, and balance.
  - Update existing client information.
  - Delete clients safely.
  - Find clients by account number.
  - List all clients with their balances.

- **Transactions**
  - Deposit money to a client account.
  - Withdraw money (with balance validation).
  - View total balances of all clients.

- **Data Persistence**
  - All client data is saved in a text file (`Clients.txt`) for permanent storage.
  - Supports loading and saving client data automatically.

---

## How It Works ⚙️

1. The program uses **structs** (`sClient`) to store client data in memory.
2. Data is read from and written to a file called `Clients.txt`.
3. A **menu-driven interface** guides the user through:
   - Main Menu: client management, transactions, exit.
   - Transactions Menu: deposit, withdraw, total balances, back to main menu.
4. Validations include:
   - Unique account numbers.
   - Withdrawals cannot exceed current balance.
   - Confirmation prompts for updates and deletions.

---

## How to Run 🖥️

1. Clone the repository:

   ```bash
   git clone https://github.com/ilyasse578/Banking-system-extension-1.git
