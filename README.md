# OTP Validation System - Python, Tkinter & MySQL Integration

## Project Overview
 
**SecureOTP** is a system designed to enhance the security of online platforms by implementing **One-Time Password (OTP)** verification. This project generates a unique OTP for users and verifies it, providing an additional layer of security beyond traditional password-based authentication.

### Key Features:
- **OTP Generation**: Generates a random 6-digit OTP.
- **Email Validation**: Validates user email format before sending OTP.
- **OTP Storage**: Stores OTP, along with the user's email, IP address, and country in a MySQL database.
- **OTP Verification**: Allows users to input OTP and checks against the database for validation.
- **Retry Mechanism**: Provides up to 3 attempts to enter the correct OTP.
- **User Feedback**: Displays success or error messages based on OTP verification.
- **IP and Country Logging**: Logs the user's IP and country for auditing and fraud detection.

### Technologies Used:
- **Python**: Core programming language.
- **MySQL**: Database for storing OTP details.
- **Tkinter**: GUI for user interaction.
- **requests**: For fetching user IP and country info.

### Benefits:
- **Improved Security**: Protects user accounts from unauthorized access.
- **Prevents Fraud**: Reduces risk of account takeovers and fake transactions.
- **Regulatory Compliance**: Helps meet security standards like GDPR and PCI-DSS.
- **Enhanced User Trust**: Provides users with a secure and reliable login process.

### Use Cases:
- **E-commerce**: Secure transactions and account access.
- **Banking**: Protects logins and financial transactions.
- **Healthcare**: Ensures protection of sensitive patient data.

![Screenshot 2024-12-30 173700](https://github.com/user-attachments/assets/531f0c6f-67f6-421e-b28b-2b05645e04ee)

