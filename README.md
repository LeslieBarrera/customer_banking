# Customer Banking System

![Banking System](images/interest.jpg) 

## Overview

This project implements a customer banking system that allows users to manage and track their savings and CD (Certificate of Deposit) accounts. The system enables users to:

- Enter and update account information.
- Calculate and track interest earned.
- View updated balances after a specified number of months.

### Project Structure

- `savings_account.py`: Contains the `SavingsAccount` class for managing savings accounts.
- `cd_account.py`: Contains the `CD` class, extending `SavingsAccount` to include CD-specific features.
- `main.py`: The entry point of the application where users interact with the banking system.
- `README.md`: This file, providing an overview and usage instructions.

## Classes and Methods

### `SavingsAccount` Class

Manages a basic savings account with balance and interest rate.

#### Methods

- **`__init__(self, balance, interest_rate)`**: Initializes a new savings account.
  - `balance`: Initial balance (float).
  - `interest_rate`: Annual interest rate (float between 0 and 1).
- **`get_balance(self)`**: Returns the current balance.
- **`get_interest(self)`**: Returns the annual interest rate.

### `CD` Class

Extends `SavingsAccount` to manage Certificates of Deposit with an additional term attribute.

#### Methods

- **`__init__(self, balance, interest_rate, term)`**: Initializes a new CD.
  - `balance`: Initial balance (float).
  - `interest_rate`: Annual interest rate (float between 0 and 1).
  - `term`: Length of the CD in months (integer).
- **`get_months(self)`**: Returns the length of the CD term in months.

## Usage Instructions

### Running the Application

1. **Clone the repository:**
   ```sh
   git clone https://github.com/LeslieBarrera/customer_banking

2. **Navigate to the project directory:**
   cd repository-name

3. **Run the application:**
   python main.py

### Example Interaction

When you run main.py, you will be prompted to enter details for savings and CD accounts. You will then be able to:

- Enter your starting balance for both savings and CD accounts.
- Input the interest rates and the term for CDs.
- Specify the number of months to calculate interest earned.
- View updated balances and interest earned after the specified period.

## Installation
Ensure you have Python installed. No additional packages are required.

## Acknowledgements
- *AI Bootcamp:* For providing the assignment and guidelines.
- *ChatGPT:* For assistance with clean code practices and README preparation.

## Contact
For questions or feedback, please contact me at lesliebarrera.d@gmail.com

