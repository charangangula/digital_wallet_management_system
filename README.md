# digital_wallet_management_system
Digital Wallet Management System
Overview
This C++ program implements a Digital Wallet Management System. It allows users to manage their financial transactions digitally by supporting transfers between users and providing an overview of user balances.

Features
Transfer Funds: Move funds from one user to another.
View Transaction Status: Output whether each transaction was successful or failed.
Display Sorted Balances: List users sorted by their remaining balance.
Input Format
Number of Users (N): An integer specifying the number of users.
User Data:
Followed by N lines, each containing:
userID (integer): The user's unique identifier.
balance (integer): The user's initial balance.
Number of Transactions (T): An integer specifying the number of transactions.
Transaction Data:
Followed by T lines, each containing:
from_userID (integer): The user ID from which funds are transferred.
to_userID (integer): The user ID to which funds are transferred.
amount (integer): The amount of funds to transfer.
Output Format
Transaction Results:
For each transaction, output either:
Success if the transaction was processed successfully.
Failure if the transaction could not be processed (e.g., insufficient funds or invalid user IDs).
Sorted User Balances:
After processing all transactions, output all users sorted by their remaining balance in ascending order.
Each line should include:
userID (integer): The user's identifier.
balance (integer): The user's remaining balance.
