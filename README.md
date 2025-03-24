PASSWORD STRENGTH CHECKER

Password Strength Checker is an application that evaluates the strength of user-entered passwords using machine learning techniques.

Table of Contents
Description

Features

Installation

Usage

Description
Password Strength Analyzer is designed to help users assess the security of their passwords. The application uses machine learning algorithms to analyze password characteristics, such as length, uppercase letters, digits, and special characters, and classifies them as Weak, Medium, or Strong.

Features
Analyzes password strength using machine learning

Extracts features like length, character types, and special symbols

Uses a Random Forest Classifier for classification

Provides real-time feedback on password strength

Installation
To run the Password Strength Analyzer locally, follow these steps:

Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/password-analyzer.git
Navigate to the project directory:

bash
Copy
Edit
cd password-analyzer
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run the script:

bash
Copy
Edit
python password_strength.py
Usage
Once the application is running:

Enter a password when prompted.

The system will analyze its strength based on predefined rules.

The output will indicate whether the password is Weak, Medium, or Strong.
