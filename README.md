## Author
Fabian Matata

## Description
Password_locker is a python application that helps the user manage password of various accounts and also helps the user generate new passwords.

## User Stories
The user would like to:
<ul>
<li>To create aan acccount for the application or log into the application.</li>
<li>Store existing accounts login credentials for the various accounts.</li>
<li>Generate new password for unregistered account and store it with the account name.</li>
<li>Delete stored account login details that I nolonger need.</li>
<li>Copy my credentials to the clipboard.</li>
</ul>

## Installation / Setup Instructions

## Specifications
## Behaviour,Input& Output
- Display codes for navigation  In terminal: $./password_locker.py  Welcome, choose an option: ca-Create Account, li-Log In, ex-Exit
- Display prompt for creating an account  Enter: ca Enter your first name, last name and password
- Display prompt for login in Enter: li Enter your account name and password
- Display codes for navigation  Successful login  Choose an option: cc - Create Credential, dc - Display Credentials, copy - Copy Credential, ex - exit
- Display prompt for creating a credential  Enter: cc Enter the site name, your username and password
- Display a list of credentials Enter: dc Prints a list of saved credentials
- Display prompt for which credential to copy Enter: copy Enter the site name of the credential you wish to copy.
- Exit application  Enter: ex Exit the current navigation stage
## SetUp / Installation Requirements
The application requires the following installations to operate:
<ul>
<li>python3.6</li>
<li>pip</li>
</ul>

## Cloning
<ul>
<li>Open Terminal {Ctrl+Alt+T}</li>
<li>Git clone https://github.com/FabianMatata/password_locker</li>
<li>cd password_locker</li>
<li>code . or atom . based on the editor you are using.</li>
</ul>

## Running the Application

- Prerequisites
- python3.6
- pip
- pyperclip
- xclip
- Cloning
## In your terminal:
  - $ git clone https://github.com/johnopana/Password-Locker/
  - $ cd Password-Locker
  - Running the Application
  - To run the application, in your terminal:
  - $ chmod +x password_locker.py
  - $ ./password_locker.py
  - Testing the Application
  - To run the tests for the class file:
  - $ python3.6 user_credentials_test.py
## Technologies Used
  - Python3.6 
## License
  - MIT ©2019 Opana John

