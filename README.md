# ATM_console_based_project

# ATM System - Python Project

## Overview

This is a simple Python-based ATM system that simulates basic banking operations such as withdrawal, deposit, pin generation, and generating mini statements. The system supports multiple accounts and ensures security by requiring a pin for sensitive operations like withdrawal and accessing the mini statement.

## Features

- **Withdraw**: Allows users to withdraw money from their accounts, provided they have sufficient balance and the correct pin.
- **Deposit**: Allows users to deposit money into their accounts.
- **Pin Generation**: Users can generate and set a pin for their account to enhance security.
- **Mini Statement**: Displays account details like name, date of birth, and balance, but only if the pin is set and entered correctly.
- **Exit**: Exits the program after performing the required tasks.

## Account Data Structure

Accounts are stored in a dictionary, where each account is associated with:
- Account Number
- User Name
- Date of Birth
- Pin (if generated)
- Account Balance

Example:

```python
accounts = {
    1001 : ["User 1", "24-08-2025", "2408", 10000],
    1002 : ["User 2", "16-04-2025", "1234", 20000],
    1003 : ["User 3", "21-09-2025", None, 10000]
}
```

## How to Use

1. **Run the script**: After cloning the repository or downloading the files, run the Python script `atm_system.py` in your terminal or IDE.
   
2. **Menu Options**: 
    - You will be presented with a menu having the following options:
        - **1**: Withdraw
        - **2**: Deposit
        - **3**: Pin Generation
        - **4**: Mini Statement
        - **5**: Exit
   
3. **Provide Inputs**: Based on the option you choose, the program will prompt you for input (e.g., account number, pin, amount, etc.).

4. **Exit the Program**: Select option 5 to exit the program after completing your actions.

## Example

```plaintext
Welcome !
********************************
1. Withdraw
2. Deposit
3. Pin Generation
4. Mini Statement
5. Exit
Enter Your option: 1
Enter Account Number: 1001
Enter Pin: 2408
Enter Amount to Withdraw: 5000
Withdraw Success
********************************
```

## Requirements

- Python 3.x
- No additional libraries required.

## How to Contribute

1. Fork the repository
2. Create a branch for your feature (`git checkout -b feature-name`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature-name`)
5. Open a pull request

## License

This project is open-source and available under the [MIT License](LICENSE).

---

This README file will help others understand your project and how to interact with it. Feel free to modify it as needed!
