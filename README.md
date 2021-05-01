# Banking Management System
Project in python with use of Tkinter GUI toolkit

## Packages required
1. Tkinter - Tkinter is the standard GUI library for Python.
2. OS - The OS module in Python provides functions for interacting with the operating system.
3. datetime - Datetime module supplies classes to work with date and time.

## Installation
###### Tkinter
```
 We just need to install Python from www.python.org, and it comes along with Python.
We do not need to install it separately.
```
###### Datetime
```
Datetime module comes build into Python, so there is no need to install it externally.
```
###### OS
```
 We just need to install Python from www.python.org, and it comes along with Python.
We do not need to install it separately.
```

## Usage
```
import os
from datetime import date
import tkinter as tk 
from tkinter import *
```

## Execution flow (How to run the program?)
###### Option 1
```
1. First extract the zip file.
2. Navigate to the file mainProject.py
3. Launch the code in any of the supporting IDE/code editors. (You must have python pre-installed in your system)
4. Run the code.
5. Now you are ready to interact with our python-based GUI program.
```
###### Option 2
```
1. First extract the zip file.
2. Navigate to the path containing extracted folder.
3. Here you can see one file named as mainProject.py
4. Now click on the location bar of Windows Explorer.
5. Then type cmd and press Enter key.
6. The command prompt will be opened in the folder.
7. Type "python mainProject.py" on command line (You must have python pre- installed in your system).
8. Now you are ready to interact with our python-based GUI program.
```

## Features of program
This is a GUI-based program. Once started running, it will prompt users to ask whose role they want to play. According to the selection, the program will ask for credentials. Once the credentials are matched, the program will unlock the respective functions
```
1) Employee
>> Admin Id and password
If id and password match then banker will unlock his/her
functionalities. If they don’t match or entered admin ID doesn't exist then appropriate error prompts are displayed.
> Functionalities:
                 1. Create bank account
                    - Account type
                    - Name
                    - Gender
                    - Nationality
                    - Account number
                    - PIN
                    - KYC document submitted e.g. Passport, Driving license, 
                    - DOB
                    - Mobile number
                    - Initial account balance
                    Above mentioned details are typed into the form.
                    - Mobile number should be of 10 digits 
                    - Valid date
                    - Unique account number
                    - Valid initial balance
                    - Valid date of birth
                    - Any one of the account type should be selected 
                    - Any one of the genders should be selected
                    - PIN should be numeric and 4 digits 
                    - PIN and re-PIN should match
                      If and only if the entered data passes through all these criteria then data is accepted and account is created successfully. Else appropriate error prompts are displayed to the user. 
                 2. Close bank account
                    - Delete the account whose account number is specified in the input area. Here it is checked whether the entered account number exists or not. If it doesn't then an error prompt is thrown.
                 3. Create admin account
                    - Admin ID
                    - Password
                    - Confirm password
                      Here above data is scanned and checked whether entered
                      admin id already exists or not & password should match the confirm the entered data passes all these checks then new admin account is created.  Else appropriate error prompts are displayed to the user.
                 4. Close admin account
                    - Delete the admin account whose admin ID are specified in the input area. Here it is checked whether the entered admin ID exists or not. If it doesn't then an error prompt is thrown. Also, it is checked that entered admin ID is not same as the ID of current logged in admin. If it is. so then it won't permit the operation. The last check applied in this functionality is that whether the password entered matches with the password associated with the entered admin ID. If it matches then admin account is closed successfully, else an appropriate error prompt is shown. are specified in the input area. Here it is checked whether the entered admin ID exists or not. If it doesn't then an error prompt is thrown. Also, it is checked that entered admin ID is not same as the ID of current logged in admin. If it is
                 5. Display Account summary
                    - Here account number is scanned from the user and all the data related to that account number is displayed on the screen. Here it is checked whether the entered account number exists or not. If it doesn't then an password. If successfully and password error prompt is thrown.
                 6. Exit
                    - Takes back to admin login screen
2) Customer            
>> Customer account number and PIN should be entered
> If account no. and PIN matches then customer will unlock his/her
functionalities. If they don’t match or entered account number doesn't exist then appropriate error prompts are displayed.
> Functionalities:
                 1. Deposit
                    greater than 25000
                    and balance is updated with the new amount.
                    - Valid amount i.e., amount cannot be negative and
                    If above criteria are satisfied then amount is deposited
                 2. Withdraw
                    - Valid amount i.e., amount cannot be greater than total balance, negative or greater than 25000
                    - Updated balance should remain at least Rs. 10,000
                    If above criteria are satisfied then amount is withdrawn and balance is updated with the new amount.
                 3. Change PIN
                    - New PIN
                    - Confirm New PIN
                    Above mentioned details are typed into the form.
                    - PIN should be numeric and 4 digits - PIN and re-PIN should match
                    If and only if the entered data passes through all these criteria then data is accepted and PIN is changed successfully. Else appropriate. error prompts are displayed to the user.
                 4. Close account
                    - PIN of the account is scanned from the user to verify if it's really the user. If PIN matches with the PIN in database then account is closed and customer login screen is displayed. If PIN doesn't match then appropriate error prompt is shown is displayed.
                 5. Check your balance
                    - On pressing this button, the total balance of customer
                 6. Exit
                    - Takes back to customer login screen
```

## Input and Output of program
We are giving a link below that redirects to the YouTube page playing our video which demonstrates the input and output of the program.
Execution video Link: [Youtube video](https://www.youtube.com/watch?v=ZyakexnOaKA)

## Contributors
1. 19BCE237 - Sakshi Sanghavi
2. 19BCE238 - Harshil Sanghvi
3. 19BCE245 - Aayush Shah
