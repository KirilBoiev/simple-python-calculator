# Password Strength Meter

A lightweight Python script that evaluates the security of a password by checking its composition. 

**Created on:** 08.06.2025

## How it works
The script analyzes the password based on five criteria:
1. **Length:** At least 8 characters.
2. **Special characters:** Contains symbols like `!@#$%^&*`.
3. **Digits:** Contains numbers.
4. **Uppercase letters:** Contains capital letters.
5. **Lowercase letters:** Contains small letters.

For every criteria met, the script adds one star (⭐) to the password strength rating.

## Features
- Provides instant visual feedback with a star rating (up to 5 stars).
- Simple and easy-to-read Python code.

## How to use
1. Run the script using Python:
   ```bash
   python main.py
