Banking Application – Java Project
Project Overview -

This is a Java-based Banking Application developed as part of the Java Programming assignment.
The program allows users to create and manage bank accounts. It is a menu-driven console application where users can perform common banking operations such as depositing, withdrawing, updating details, and viewing account information.

The project makes use of basic Java concepts such as:

Classes and Objects

Arrays

Control Structures (loops, if-else, switch)

Methods

String handling and user input with Scanner

Features Implemented -

Create Account – User can create a new bank account by providing name, email, phone, and an initial deposit.

Deposit Money – User can add money to an account (only if the amount is positive).

Withdraw Money – User can withdraw money if there is sufficient balance.

View Account Details – Displays account number, holder name, balance, email, and phone.

Update Contact Details – Allows updating email and phone number of an account holder.

List All Accounts – Displays details of all created accounts (extra functionality for better overview).

Exit – Ends the program safely.

How the Code Works -

The program is divided into three main classes:

Account class – Represents a single bank account. Contains attributes (account number, name, balance, email, phone) and methods to deposit, withdraw, show details, and update contact info.

BankApp class – Handles all user interactions. Stores multiple accounts in an array and provides methods for creating accounts, searching accounts, depositing, withdrawing, updating, and listing.

BankingAppMain class – Contains the main() method that starts the application and shows the menu.

When the program runs, it displays a menu with choices (create, deposit, withdraw, etc.).

The user selects an option, enters the required inputs, and the program performs the operation.

Accounts are stored in an array, so multiple accounts can be managed in a single run.
