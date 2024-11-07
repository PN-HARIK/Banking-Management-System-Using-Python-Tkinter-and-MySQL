# Banking-Management-System-Using-Python-Tkinter-and-MySQL

A simple banking application built using Python and Tkinter with functionalities for registering, logging in, depositing, withdrawing, balance inquiry, and fund transfer. The application interfaces with a MySQL database to store and retrieve user information securely.

Features
User Registration: Users can register by providing their details (username, password, contact number, etc.).
User Login: Users can log in to access banking functionalities.
Deposit and Withdrawal: Allows users to deposit and withdraw money from their account.
Balance Inquiry: Displays the current balance in the user's account.
Fund Transfer: Transfer funds to other accounts within the application.
Logout: Log out from the current session.

Requirements
Python 3.x
Tkinter (usually comes pre-installed with Python)
pymysql
MySQL Database (for storing user and transaction data)
Install the required dependencies with:

Project Structure
main_account_screen: Entry point with options to Login, Register, Deposit, Withdraw, Balance Inquiry, and Fund Transfer.
register(): Registers a new user and saves their details to the database.
login(): Allows registered users to log in to their accounts.
deposit(): Lets the user deposit an amount into their account.
withdraw(): Lets the user withdraw an amount from their account.
balance(): Shows the user their current account balance.
fund_transfer(): Allows the user to transfer funds to other accounts.
