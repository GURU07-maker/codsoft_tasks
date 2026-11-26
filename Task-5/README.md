Task 5: Contact Book

Description:-
A simple command-line Contact Book application written in Python. It stores contact names, phone numbers, email addresses, and physical addresses while the program is running.

Features:-
- Add a contact with name, phone number, email, and address.
- View the names and phone numbers of saved contacts.
- Search for contacts using a name or phone number.
- Update a contact by searching for the exact name.
- Delete a contact by searching for the exact name.
- Exit the application.

Requirements:-
- Python 3
- No external libraries are required.

How to Run:-
This project is provided as a Jupyter Notebook (`TASK 5.ipynb`).

1. Open the notebook in Jupyter Notebook, JupyterLab, or VS Code.
2. Run the code cell.
3. Choose an option from the menu and follow the prompts.

How to Use:-
- `1` adds a contact.
- `2` displays saved contact names and phone numbers.
- `3` searches by name or phone number.
- `4` updates a contact after entering the contact's current name.
- `5` deletes a contact after entering the contact's name.
- `6` exits the application.

Concepts Used:-
Python lists, nested lists, `while` loop, `for` loop, conditional statements, string methods such as `lower()`, and list methods such as `append()` and `remove()`.

Note:-
Contacts are stored in a list in memory. They are not saved to a file or database, so they are lost when the program stops. The update and delete options match the entered name exactly, ignoring uppercase and lowercase differences.
