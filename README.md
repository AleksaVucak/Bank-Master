# Bank Master
The Banking System project is a Java-based application designed to simulate a real-world banking environment. It allows for user registration, account management, transaction processing, and administrative controls. This multi-functional project leverages OOP concepts such as inheritance, polymorphism, and custom exception handling to create a robust and scalable system.

## Features
### User Registration
Register new customers with unique usernames
### Account Management
- Open Chequing/Savings accounts.
- View account details and transaction history.
- Update account information (address, phone number, etc.)
### Transaction Processing
- Deposit and withdraw funds.
- Transfer money between accounts
- Automatically apply interest to savings account.
### Admin Controls
- Monitor all existing accounts
- Generate detailed account reports asyncronously.
### Error Handling
Custom exceptions for invalid inputs and insufficient funds.

## Usage
### Main Menu Options
#### Register New Customers
Add new users to the system.
#### Open Accounts
Create a new Chequing/Savings account for an existing user.
#### Perform Transactions
Conduct deposits, withdrawals, or transfers.
#### View Account
Check account details and transaction history.
#### Search Accounts
Search for account within the database by name, username, or account number.
#### Generate Report
Create a detailed report of all accounts and transactions
#### Update Account Information
Modify address and/or phone number.
#### Admin Actions
Monitor all accounts or generate reports (requires admin password)

## Key Classes
### User
Represents a bank customer
### Account
Base class for Chequing and Savings accounts.
#### ChequingAccount
Handles chequing specific operations.
#### SavingsAccount
Includes interest calculation and application.
### Transaction
Represents a financial transaction between two users, or from multiple accounts from the same user.
### Bank
Core logic for account and user management.
### Admin
Provides administrative privileges.
### ConsolePrinter
Ensures syncronized console outputs.
### Custom Exceptions
#### InvalidInputException
For invalid user inputs (Incorrectly formatted user inputs).
#### InsufficientFundsException
For transactions exceeding the users account balance.

## Security Note
Admin Password: admin123
- The password is hardcoded for this project but should be stored securely in a real-world application

## File Structure
### BankingSystem.java
Main file containing all the classes and logic.
### accounts_report.txt
Generated report file containing account details and transaction history.

## Prerequisites
- Java Development Kit (JDK), Version 8 or higher.
- A code editor or IDE
> I used IntelliJ for this particular project.

## Installation
1) Clone the repository or download the project file titled 'BankingSystem.java'
2) Ensure you have the required JDK installed.

## How to Run
1) Navigate the project directory
2) Compile the program:
> javac BankingSystem.java
3) Run the program:
> java BankingSystem

## Future Improvements
- Implement persistent data storage using a database.
- Introduce multi-factor authentication for admin access.
- Enhance the user interface with a graphical interface (e.g., JavaFX or Swing).
> Turn this into a web application using the existing CLI logic/concepts
- Add more account types and features, such as loans or fixed deposits.

## Contact
For any questions, feedback, or collaboration opportunities, feel free to reach out:
- Name: Aleksa Vucak
- Email: aleksavucak@gmail.com
- LinkedIn: www.linkedin.com/in/aleksa-vucak-587923298
