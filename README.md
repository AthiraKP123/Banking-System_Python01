# Banking System

Explanation:
- This code creates a BankAccount class with methods for login, deposit, withdrawal, and checking the balance.
- The main() function demonstrates how to use this class by creating an account, logging in, and performing various banking operations based on user input.
- It uses a predefined list (`accounts_info`) containing dictionaries with account details such as account number, PIN, and initial balance.
- Instances of `BankAccount` are created for each account holder using the information from `accounts_info`.
- The program prompts the user to enter their account number and PIN.
- It validates the entered credentials against the predefined account information and provides 
  banking functionalities (deposit, withdraw, check balance) based on user input. For that here used while loop and the loop continues until the user chooses to exit.
- After each operation, it prompts the user to press Enter to continue, maintaining the flow of the program.

Note: This code assumes a basic scenario and lacks robust error handling, input validation, and data persistence (like storing accounts in a database). In a real-world scenario, these aspects are crucial for security and stability.
