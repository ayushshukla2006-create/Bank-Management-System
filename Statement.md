Bank Management System --- Project Statement

1. Problem Statement

Managing basic bank account operations requires maintaining customer
information, account numbers, and account balances while ensuring that
deposits and withdrawals follow valid conditions.

The objective of this project is to develop a simple console-based Bank
Management System using Core Java and Object-Oriented Programming. The
system provides a structured way to create accounts, store account
information, deposit and withdraw money, and check account details.

The project also demonstrates the practical use of the Java HashMap
data structure for storing and retrieving account objects using account
numbers.

2. Scope of the Project

The current project focuses on implementing basic banking operations
through a menu-driven console application.

In Scope

Creating a new bank account.

Automatically generating account numbers starting from 1001.

Storing customer name and account balance.

Depositing money into an existing account.

Withdrawing money from an existing account.

Checking account details and current balance.

Searching for an account using its account number.

Basic validation of deposit and withdrawal amounts.

Handling non-existing account numbers.

Providing a simple console-based user interface.

Out of Scope

The current version does not include:

Graphical user interface.

Database connectivity.

User authentication or PIN/password protection.

File-based persistent storage.

Transaction history.

Online banking or network functionality.

ATM integration.

These features may be considered for future versions.

3. Target Users

The primary target users of this project are:

Students learning Core Java and Object-Oriented Programming.

Beginners learning Java collections such as HashMap.

Users who want to demonstrate basic banking operations through a
console application.

Academic evaluators who need to assess the implementation of Java
programming concepts in a practical project.

The application is primarily an educational project rather than a
production banking system.

4. High-Level Features

4.1 Open New Account

The user can create a new bank account by entering their name and
initial deposit. The system automatically assigns an account number
starting from 1001.

4.2 Deposit Money

The user can deposit money by providing a valid account number and
deposit amount. The system updates and displays the new balance.

4.3 Withdraw Money

The user can withdraw money from an existing account. The system
validates the amount and prevents withdrawals greater than the available
balance.

4.4 Account Details / Balance Enquiry

The user can enter an account number to view the account number,
customer name, and current balance.

4.5 Basic Validation

The system rejects invalid transaction amounts, negative initial
deposits, withdrawals exceeding the available balance, and requests for
accounts that do not exist.

4.6 Menu-Driven Console Interface

The system provides a numbered menu that allows the user to select
banking operations repeatedly until choosing the Exit option.

5. Project Summary

The Bank Management System is a Core Java learning project that combines
Object-Oriented Programming, HashMap, Scanner, loops, conditional
statements, and switch-case control to implement a basic banking
workflow.

The project is designed to provide a foundation for future enhancements
such as file persistence, database integration, authentication,
transaction history, and a graphical or web interface.
