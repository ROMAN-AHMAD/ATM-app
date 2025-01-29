# ATM Machine App - Java

## Overview
The **ATM Machine App** is a Java-based application that simulates the functionalities of a real ATM. Users can log in using their credentials and perform various banking operations such as checking balance, withdrawing money, depositing money, and viewing transaction history.

## Features
- **User Authentication:** Secure login system to access the ATM.
- **Balance Inquiry:** View the current account balance.
- **Cash Withdrawal:** Withdraw a specific amount from the account.
- **Deposit Funds:** Add money to the account balance.
- **Transaction History:** Keep track of past transactions.
- **Exit Option:** Safely exit the application.

## Prerequisites
To run this project, ensure you have:
- **Java Development Kit (JDK) 8 or later** installed
- An **IDE** (such as IntelliJ IDEA, Eclipse, or NetBeans) or a terminal for execution

## Installation & Setup
1. **Clone the Repository** (or download the source code):
   ```bash
  [ git clone https://github.com/your-repo/atm-machine-java.git
   cd atm-machine-java](https://github.com/ROMAN-AHMAD/ATM-app)
   ```

2. **Compile the Java Files**:
   ```bash
   javac *.java
   ```

3. **Run the Application** (starting from the `Login` class):
   ```bash
   java Login
   ```

## Project Structure
```
ATM-Machine-Java/
│── Login.java          # Handles user authentication
|__SignUp.java
│── ATM.java            # Main ATM functionalities
│── Account.java        # User account management
│── Transaction.java    # Manages transaction history
│── BankDatabase.java   # Stores user data and balances
│── README.md           # Project documentation
```

## How to Use
1. Run the `Login.java` class.
2. Enter valid user credentials.
3. Choose an option from the ATM menu:
   - Check balance
   - Withdraw cash
   - Deposit money
   - View transaction history
   - Exit
4. Perform transactions as needed and log out safely.

## Future Enhancements
- Implement a **database connection** for persistent storage.
- Add a **graphical user interface (GUI)** using JavaFX or Swing.
- Introduce **multi-user support** with individual accounts.

## License
This project is open-source and available under the MIT License.

## Author
Developed by **Roman Ahmad
