# Atm_box
ATM PIN Checker SystemThis project is a simple Python-based ATM PIN verification and withdrawal system. It simulates the basic security and transaction flow of an Automated Teller Machine. Users must enter the correct PIN to access their account and perform withdrawals. After three incorrect attempts, the system blocks access for security purposes.
Features
1. PIN Verification
User must enter the correct 4-digit PIN.
Allows up to three incorrect attempts.
Blocks the account after the third failed attempt.

2. Withdrawal System
Displays current account balance after successful PIN entry.
Allows user to enter a withdrawal amount.
Validates the amount (no negative or zero values).
Checks for sufficient account balance.
Updates and displays the new balance after a successful withdrawal.

3. Error Handling

Prevents program crash due to invalid inputs (e.g., letters instead of numbers).
Provides clear messages for invalid PIN, invalid input, or insufficient funds.
How It Works
Program starts and requests the user to enter their PIN.
If the PIN is correct:
Balance is displayed.
User can enter withdrawal amount.
System checks and completes the transaction if valid.
If the PIN is incorrect:
The user is informed.
Remaining attempts decrease.
After 3 incorrect attempts, the account is locked.


Code Overview
The program uses:
Variables to store balance, PIN, and attempts
A loop for retrying PIN entry
Conditional statements to validate PIN and transactions
Try/except blocks to prevent invalid input crashes

How to Run
Install Python (if not already installed).
Save the script as atm_pin_checker.py.
Run the program:
