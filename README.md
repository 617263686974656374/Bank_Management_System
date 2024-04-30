# Bank_Management_System
The Bank Management System is a Java-based application designed to manage banking operations efficiently. 
It provides a comprehensive environment for handling client accounts, including the ability to add new clients, manage accounts, and perform transactions such as deposits and withdrawals. This program is ideal for educational purposes and provides a practical demonstration of object-oriented programming concepts, data handling, and user interaction through console-based menus.

### Key Features
- **Client Management:** Users can add new clients to the bank, each with unique IDs and one or more accounts. The system ensures that all client IDs and account numbers are unique through the use of sets.
  
- **Account Operations:** Each client can have multiple accounts. The system allows for the creation of accounts and links them to specific clients. Users can deposit and withdraw money, ensuring that transactions are only completed if they meet the necessary criteria (e.g., sufficient funds are available).

- **Interactive Menus:** The program includes several menus that guide the user through different functionalities such as adding or deleting clients, displaying accounts, and handling transactions. Menus are easy to navigate and provide clear instructions for users.

- **Transaction Handling:** The system includes methods to deposit and withdraw funds from accounts. These operations update the account's balance and reflect the changes immediately within the system.

- **Data Validation:** Input from users is validated for correctness and completeness. The system checks that inputs like client IDs and account numbers are integers and manages errors gracefully without crashing.

- **Security Features:** Basic checks are implemented to ensure that only authorized users can access and manipulate account information. For example, before performing any operations, users must verify their identity by providing their client ID and account number.

### Program Structure
- **Main Class:** Initializes the system and starts the user interaction loop.
- **Client Class:** Defines the properties and methods related to clients, including name, surname, client ID, and a list of accounts.
- **Account Class:** Handles properties and methods related to accounts, such as the account number and balance, along with methods to deposit and withdraw money.
- **BankSystem Class:** The core class that manages all operations within the bank. It handles the creation of clients and accounts, transactions, and user interactions through various menus.

### Usage Example
When the program is run, it presents a main menu with options to navigate to staff or client sections. Here's a brief run-through:

1. **Starting the Program:**
   - The application is launched, and the main menu is displayed:
     ```
     Bank Fohnsdorf
     [1] Staff section
     [2] Client section
     [0] exit program
     Enter index of your choice:
     ```

2. **Adding a Client:**
   - Navigate to the staff section and select to add a new client. Enter the client's name, surname, and the system will generate a unique ID and account number.

3. **Making a Deposit:**
   - Switch to the client section, verify the client's identity, and select the deposit option. Enter the amount to be deposited and confirm the transaction.

This system is an effective tool for understanding the basics of banking operations and the underlying technology driving these processes in a simplified environment.
