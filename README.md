# OTP-Email-verification-system
OTP Email Verification System
This Python script allows users to receive a One-Time Password (OTP) via email for verification. The script generates a random OTP, sends it to the user's email, and prompts the user to enter the received OTP for validation.

🚀 Features
✅ Secure email sending using SMTP (Gmail SMTP Server)
✅ Environment variable support for email credentials (No hardcoded passwords!)
✅ Valid email format check before sending OTP
✅ Automatic OTP generation (4-digit random number)
✅ Error handling for SMTP failures and invalid user input

🔧 Prerequisites
Before running the script, ensure you have:

Python 3 installed

A Gmail account with App Passwords enabled

Required Python libraries:

pip install smtplib email
🛠 Setup

export EMAIL_USER="your_email@gmail.com"
export EMAIL_PASS="your_app_password"

Enter the number of users for OTP verification.

Provide a valid email address for OTP delivery.

Check your email inbox for the OTP.

Enter the OTP in the terminal for verification.

Get a success message if the OTP matches, otherwise retry.

📌 Future Enhancements:
🚀 Support for Twilio or other SMS OTP services
🔐 Database integration to store OTPs securely
📧 Support for multiple email providers

















