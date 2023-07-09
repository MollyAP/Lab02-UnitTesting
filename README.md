# ATM Console Application

**Author:** Mollemira Porphura (Molly)
**Version:** 1.0.0

## Overview

This is a console application that mocks the functionality of an ATM and lets you view your account balance, withdraw money, and deposit money.

## Getting Started

To use this application, follow these steps:

1. Clone the repository or download the source code files.
2. Open the solution in your preferred C# IDE.
3. Build the solution to compile the code.
4. Run the application.

## Example

Once the application is running, you will see a menu of options. Here's an example of how you can interact with the ATM:

1. View Balance
2. Withdraw
3. Deposit
4. Exit
Enter your choice: 1

Current Balance: $0.00

1. View Balance
2. Withdraw
3. Deposit
4. Exit
Enter your choice: 3

Enter amount to deposit: 100.00
Deposited: $100.00

1. View Balance
2. Withdraw
3. Deposit
4. Exit
Enter your choice: 2

Enter amount to withdraw: 50.00
Withdrawn: $50.00

1. View Balance
2. Withdraw
3. Deposit
4. Exit
Enter your choice: 4

Exiting...


## Architecture

The application is built using C# and follows a console-based architecture. It consists of a single `ATM` class with static methods for viewing the balance, withdrawing money, and depositing money. The `UserInterface` method handles the user interaction by presenting a menu of options and executing the chosen operation.

## Change Log

- 1.0.0: Initial version of the ATM console application.

