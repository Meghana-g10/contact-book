INTRODUCTION

In the digital age, efficient management of personal and professional contacts is essential.
Traditional contact storage methods—such as handwritten diaries, disorganized
spreadsheets, or limited-function mobile apps—often lack features like structured
categorization, validation, and scalability. This project presents a desktop-based Contact
Book application developed using Python, offering a clean and intuitive interface alongside
secure local storage and robust data manipulation tools.
Built using Python’s Tkinter for GUI and SQLite for backend storage, the Contact Book
empowers users to seamlessly perform contact-related operations such as adding, searching,
editing, and deleting entries. The modular architecture ensures maintainability and opens
the door for future feature expansions like contact grouping, CSV export, and cloud
synchronization.

Objective of project

The primary objective of this Contact Book project is to design and implement a user-
friendly, desktop-based application that facilitates efficient management of personal and
professional contact information. It aims to eliminate the clutter and limitations of
conventional contact storage methods by providing a structured, searchable, and editable
digital solution using Python.

Key goals include:

● Contact Management: Enable users to store, view, and organize contacts in a single,
accessible interface.
● Fast and Accurate Retrieval: Implement search functionality to quickly locate contacts
using key fields such as name, phone number, or email.
● Edit and Update Capabilities: Allow seamless editing and deletion of outdated or incorrect
entries.
● Robust Architecture: Utilize Python’s Tkinter for the GUI and SQLite for backend data
storage, ensuring secure and scalable performance.
● Data Integrity and Validation: Incorporate input checks to prevent erroneous data entries
and ensure consistency.
● Extendability: Lay the foundation for future upgrades, such as importing/exporting data,
cloud sync, and mobile integration.

MODULES AND METHODS USED
MODULES:

1. json
Used to store and retrieve contact data in JSON format.
Enables persistent storage of contact information (name, phone, email, etc.).
2. os
Used for file handling operations like checking if the contact file exists.
Helps to create or remove files based on application logic.
3. tkinter
Provides the graphical user interface (GUI) components like buttons, labels,
Text boxes etc.
Allows easy creation of windows for adding, editing, searching, and deleting
Contacts.

METHODS:

1. Contact Management Module:
Purpose:
Handles the creation, update, deletion, and search of contact records.
Key Functions/Methods:
• add_contact():
Adds a new contact to the contact book and saves it to the JSON file.
• delete_contact():
Removes a selected contact from the data.
• edit_contact():
Modifies the existing contact details.
• search_contact(): Searches contacts by name or phone number.
• save_to_file() / load_from_file(): Functions to write and read contacts from a .json file to maintain data persistence.

3. GUI Handling Module: Purpose: Provides a user-friendly interface to interact with the contact book. Key Functions/Methods: • Tk():
Initializes the main GUI window.
• Label, Entry, Button, Listbox: Widgets used to display and receive input from the user.
• command: Binds buttons to the backend functions like add, edit, delete.
• pack()/grid(): Layout methods used to arrange widgets in the window
