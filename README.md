# Password Strength Checker

Password Strength Checker is an application that evaluates the strength of user-entered passwords using machine learning techniques.

## Table of Contents
- [Description](#description)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Contact](#contact)

## Description
Password Strength Checker is designed to help users assess the security of their passwords. The application leverages machine learning algorithms to analyze password characteristics—such as length, uppercase letters, digits, and special characters—and classifies them as **Weak, Medium, or Strong**.

## Features
- 🔍 **Analyzes password strength** using machine learning
- 🛠 **Extracts features** like length, character types, and special symbols
- 🌲 **Utilizes a Random Forest Classifier** for classification
- ⚡ **Provides real-time feedback** on password security

## Installation
To run the Password Strength Checker locally, follow these steps:

### **1. Clone the repository:**
```sh
git clone https://github.com/your-username/password-analyzer.git
```

### **2. Navigate to the project directory:**
```sh
cd password-analyzer
```

### **3. Install dependencies:**
```sh
pip install -r requirements.txt
```

### **4. Run the script:**
```sh
python password_strength.py
```

## Usage
Once the application is running:

1. 🔑 **Enter a password** when prompted.
2. 📊 **The system will analyze** its strength based on predefined rules.
3. ✅ **The output will indicate** whether the password is **Weak, Medium, or Strong**.
