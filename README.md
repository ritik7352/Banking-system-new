# Banking-system
 This project refers to a console-based application that simulates fundamental banking operations. It involves creating and managing bank accounts, including functionalities such as deposits, withdrawals, checking account balances, closing accounts, and viewing all active accounts.
 The system is designed to keep data persistent across sessions using file storage. It utilizes object-oriented programming principles to encapsulate account management within an Account class and the overall banking operations in a Bank class.
 The code includes error handling to manage financial constraints like maintaining a minimum account balance.
 
Input
The user interacts with the banking system through a menu-driven interface, providing inputs based on the operation they wish to perform. These inputs include: 

Account Creation:
First Name
Last Name
Initial Balance
Account Operations:
Account Number (for accessing a specific account)
Amount for deposit or withdrawal
Menu Selection:
Choice of operation (Open Account, Deposit, Withdraw, etc.)
Output
The program provides various outputs in response to user actions:

Account Details: Displays account information, including account number, first name, last name, and balance.
Transaction Confirmation:
Confirmation of successful deposit or withdrawal.
Error message if a withdrawal request would cause the balance to fall below the minimum limit.
Account Closure: A message indicating that an account has been successfully closed.
All Accounts Overview: Displays the list of all existing accounts with their details.
