# Elevate-Labs--Task5
Bank Account Simulation

Features:

Account Creation: Initialize an account with an account number and initial balance.

Deposit: Add money to the account (positive amounts only).

Withdrawal: Remove money from the account if sufficient funds are available.

Balance Inquiry: Check the current account balance.

Transaction History: Record and display all transactions (deposits, withdrawals, and account creation).

Code Explanation:

Class Structure:

The BankAccount class encapsulates account details like accountNumber, balance, and transactionHistory (stored in a List<String>).

Constructor initializes the account and logs the creation in the transaction history.

Methods:

deposit(double amount): Adds funds if the amount is positive, updates balance, and logs the transaction.

withdraw(double amount): Deducts funds if sufficient and valid, updates balance, and logs the transaction.

getBalance(): Returns the current balance.

getAccountNumber(): Returns the account number.

printTransactionHistory(): Displays all recorded transactions.

Main Method:

Creates a sample account with an initial balance of $1000.

Performs test transactions: deposits $500, withdraws $200, attempts an invalid withdrawal of $2000, and an invalid deposit of -$50.

Outputs the final balance and transaction history.

Dependencies:

Java standard library (no external dependencies required).

Ensure java.util.List and java.util.ArrayList are available (included in JDK).

Notes:

The program includes input validation to prevent negative deposits or overdrafts.

Transaction history is stored in memory (not persisted to a file).



Extend the program by adding features like multiple accounts, interest calculations, or file-based persistence for advanced use cases.
