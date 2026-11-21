# Task 3: Password Generator

## Description
A simple Python program that generates a random password based on a length entered by the user. The password can contain uppercase and lowercase letters, digits, and punctuation characters.

## Features
- Takes the desired password length from the user.
- Checks that the length is greater than zero.
- Builds a character set using letters, digits, and punctuation.
- Selects random characters to create the password.
- Displays the generated password.

## Requirements
- Python 3
- Python standard-library modules: `random` and `string`
- No external installation is required.

## How to Run
This project is provided as a Jupyter Notebook (`TASK 3.ipynb`).

1. Open the notebook in Jupyter Notebook, JupyterLab, or VS Code.
2. Run the code cell.
3. Enter a positive password length when prompted.
4. The generated password will be displayed.

## Concepts Used
Python modules, variables, string operations, `for` loops, `range()`, `random.choice()`, and conditional statements.

## Security Note
This beginner project uses Python's `random` module for learning purposes. For passwords intended to protect real accounts, use Python's `secrets` module, which is designed for security-sensitive random values.
