README - Email Client Application

This document provides instructions for setting up and running the SMTP and IMAP email client application developed in Python using the PyQt5 framework.

Prerequisites

Before running the application, ensure you have the following installed on your system:

Python 3.x
PyQt5
smtplib (standard library)
imaplib (standard library)
email (standard library)

Using App Passwords

For enhanced security, it is recommended to use app-specific passwords. For Gmail accounts, generate an app password through your Google Account settings under 'Security' -> 'App passwords'. Use this app password instead of your Google account's original password when logging in through the application.

SMTP Client Setup

To configure the SMTP client:

Enter your email address and the app-generated password.
Click 'Login' to authenticate and open the main application screen.
Specify the recipient's email address, and set the SMTP server to 'smtp.gmail.com' with port 587 for TLS.
Type your email content and send.

IMAP Client Setup

To access the IMAP client:

Enter the same credentials used for SMTP (email and app-generated password).
Click 'Login' to access your inbox.
Use the refresh button to retrieve and view recent emails.

Running the Application

To run the SMTP client application, execute the following command:

python SMTP.py

To run the IMAP client application, execute the following command:

python IMAP.py