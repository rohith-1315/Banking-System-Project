Bank Management System

A console-based Bank Management System in C++ that simulates essential banking functions, such as opening accounts, handling deposits and withdrawals, transferring funds, closing accounts, and displaying account details.

Description

This Bank Management System allows users to:
- Create and manage multiple accounts.
- Make deposits and withdrawals.
- Transfer money between accounts.
- View details for all accounts.
- Close accounts as needed.

How to Use

1. Compile and Run the Program:
   - Clone the repository and navigate to the project directory.
   - Compile the program with a C++ compiler:
     bash
     g++ main.cpp -o BankManagementSystem
     
   - Run the compiled program:
     bash
     ./BankManagementSystem
     

2. Interact with the Menu:
   - After starting, a menu will display with options to open accounts, make deposits or withdrawals, transfer funds, and more.

Example Usage

This example demonstrates typical usage of the system, including opening accounts, making a deposit, and transferring funds.

Step-by-Step Walkthrough

1. Open an Account

When prompted, select 1 to open a new account. Enter the following details when prompted:

- Name: Rajesh Kumar
- Gender: M
- Age: 35
- Account Type: S (Savings)
- Initial Deposit: 500

Expected output:

Enter name: Rajesh Kumar
Enter gender (M/F): M
Enter age: 35
Enter account type  S-savings or C-current (S/C): S
Minimum deposit for Savings account is 500.
Enter initial deposit amount (>= 500): 500
Your account number is: 1
Account added successfully


2. Deposit Money

Select 3 to make a deposit. When prompted, enter:

- Account Number: 1
- Deposit Amount: 1000

Expected output:

Enter account number: 1
Enter deposit amount: 1000
Deposit successful. New balance: 1500.00


3. Open Another Account

To demonstrate transferring funds, let's open a second account.

- Name: Anjali Sharma
- Gender: F
- Age: 28
- Account Type: C (Current)
- Initial Deposit: 0

Expected output:

Enter name: Anjali Sharma
Enter gender (M/F): F
Enter age: 28
Enter account type  S-savings or C-current (S/C): C
Your account number is: 2
Account added successfully


4. Transfer Funds

Select 6 to transfer funds between accounts. Enter the following:

- Your Account Number: 1
- Recipient Account Number: 2
- Transfer Amount: 700

Expected output:

Enter your account number: 1
Enter recipient account number: 2
Enter transfer amount: 700
Transfer successful. Remaining balance: 800.00


5. Show All Accounts

Select 4 to view details of all accounts. Expected output:


=== All Accounts in ===
Account Holder: Rajesh Kumar
Gender: M
Age: 35
Account Type: S
Account Number: 1
Balance: 800.00
-------------------------
Account Holder: Anjali Sharma
Gender: F
Age: 28
Account Type: C
Account Number: 2
Balance: 700.00
-------------------------


6. Close Account

To close an account, select 5 and enter the account number:

- Account Number: 2

Expected output:

Enter account number to close: 2
Account closed successfully.


Sample Menu Output

The menu will continue to display until you select 8 to exit the program.

---
