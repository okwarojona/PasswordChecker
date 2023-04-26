### Password Checker
+ This script checks if a given password has been exposed in any data breaches using the Pwned Passwords API.

### Prerequisites
+ Python 3.x
+ requests module
### Installation
+ You can install the requests module using pip:
pip install requests
### Usage
+ Save the script in a file named password_checker.py
+ Run the script by executing the following command in your terminal:
python password_checker.py password1 password2 password3 ...

+ Replace password1, password2, password3, etc. with the passwords you want to check.

Example:
python password_checker.py mypassword 123456 letmein
+ The script will check each password and print a message indicating whether the password was found in any data breaches or not.
