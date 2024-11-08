# EmailJet

# SMTP Email Sending Application
This project demonstrates how to send emails using the SMTP (Simple Mail Transfer Protocol) protocol, with a focus on sending emails with text content and attachments. 

The application utilizes Python's smtplib and ssl libraries to securely send an email through Gmail's SMTP server.

# Features
Send an email with a subject, body, and attachment.
Use TLS encryption for secure communication between the client and the Gmail SMTP server.

Configurable sender and receiver email addresses.

Supports sending plain text files as attachments.

# Prerequisites
Before running this project, ensure you have the following:

A Gmail account with App Passwords enabled (if 2FA is enabled on your account).

The Python 3.x environment set up on your machine.

The client file (client-file.txt) you wish to attach in the email.

# Requirements
You need to install the following Python libraries:

smtplib (comes pre-installed with Python)

ssl (comes pre-installed with Python)

email (comes pre-installed with Python)

# Setup
Create an App-Specific Password:

If you have 2-factor authentication enabled for your Gmail account, you will need to generate an App-Specific Password to log in via SMTP. You can generate one here.

Clone this repository:

On terminal : python server.py

# Update Email Credentials:

Replace the email_sender and email_password variables with your Gmail address and the app-specific password.
Prepare the Attachment:

Ensure the file you wish to attach (e.g., client-file.txt) is in the same directory or provide the correct path to the file.

# Running the Project
Ensure you have set up the required email configurations.
Open a terminal or command prompt in the directory where your Python script is located.
Run the Python script:
bash
Copy code
python server.py
If the email is successfully sent, the message Email sent successfully. will appear in the terminal. If there is an error, it will print the error message.

![image](https://github.com/user-attachments/assets/4c12aaa9-2cd7-47c1-b85b-b9528c42640a)
