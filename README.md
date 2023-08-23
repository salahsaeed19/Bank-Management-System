# Bank Management System using tkinter

This code snippet demonstrates a simple bank management system implemented with the tkinter library, providing functionalities for creating accounts, logging in, performing credit and debit operations, and displaying transaction histories.

## Getting Started

Before running the code, ensure you have the necessary libraries installed. You can install tkinter as it is a standard library for GUI development in Python.

## Code Explanation

The code is divided into several functions, each catering to a specific aspect of the bank management system. Here's a brief overview:

1. **`is_number(s)`**: This function checks whether a given string can be converted to a floating-point number.

2. **`check_acc_nmb(num)`**: This function checks if an account number file exists, indicating a valid account.

3. **`home_return(master)`**: This function returns to the main menu from other windows.

4. **`write(master, name, oc, pin)`**: This function is used to create a new account, writing account details to files.

5. **`crdt_write(master, amt, accnt, name)`**: This function handles crediting an amount to an account and updates transaction records.

6. **`debit_write(master, amt, accnt, name)`**: This function handles debiting an amount from an account and updates transaction records.

7. **`Cr_Amt(accnt, name)`**: This function creates a GUI window for crediting an amount.

8. **`De_Amt(accnt, name)`**: This function creates a GUI window for debiting an amount.

9. **`disp_bal(accnt)`**: This function displays the account balance in a messagebox.

10. **`disp_tr_hist(accnt)`**: This function displays the transaction history in a GUI window.

11. **`logged_in_menu(accnt, name)`**: This function creates the main logged-in menu with buttons for various operations.

12. **`logout(master)`**: This function logs the user out and returns to the main menu.

13. **`check_log_in(master, name, acc_num, pin)`**: This function verifies login credentials and opens the logged-in menu.

14. **`log_in(master)`**: This function creates a GUI window for user login.

15. **`Create()`**: This function creates a GUI window for account creation.

16. **`Main_Menu()`**: This function is the starting point for the main menu of the bank management system.

## Usage

1. Run the script. The main menu will be displayed.

2. Choose between "Create Account" or "Log In" options to proceed.

3. If creating an account, fill in the required details.

4. If logging in, enter the necessary credentials.

5. Once logged in, you can perform credit, debit, and balance check operations, as well as view transaction history.

## Clean Up

The code doesn't involve any external resources that require cleanup. However, you can add error handling and additional features to enhance the user experience.

