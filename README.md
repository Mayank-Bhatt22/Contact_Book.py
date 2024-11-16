# Contact_Book.py
Contact Book Application
This Python script is a simple Contact Book Application that allows users to manage their personal contact information interactively. It uses a dictionary to store and manage contacts, where each contact's name serves as the key, and the value is another dictionary containing details such as age, email, and mobile number. Below is a detailed explanation of the functionality:

Key Features:
Create Contact:

Allows the user to add a new contact by entering details like name, age, email, and mobile number.
Ensures duplicate contact names are not allowed by checking if the name already exists in the dictionary.
View Contact:

Lets the user view the details of a specific contact by entering the contact's name.
Displays the contact's name, age, email, and mobile number if found, otherwise shows an error message.
Update Contact:

Enables the user to update an existing contact's details (age, email, or mobile number).
Checks if the contact exists before allowing updates.
Delete Contact:

Allows the user to delete a contact by specifying the name.
Ensures the contact exists before attempting to delete it.
Search Contact:

Lets the user search for a contact by entering part of the name (case-insensitive search).
Displays all matching contacts or shows an error if no matches are found.
Count Contacts:

Displays the total number of contacts currently stored in the contact book.
Exit:

Exits the program with a goodbye message.
How It Works:
The program runs inside a while loop to provide continuous interaction until the user chooses to exit.
The contacts dictionary acts as the database, storing each contact's information.
The user interacts with the program through a menu system, choosing options by entering numbers (1–7).
Each choice corresponds to a specific functionality, with validation for incorrect inputs.
Improvements and Fixes:
Logic Corrections:

Replace choice == '1' and others with choice == 1 to handle integer input properly.
Fix variable contact = contact[name] in View Contact to properly access contact details.
Ensure age, email, and mobile are defined before use in Search Contact.
Enhancements:

Input validation for fields like age (should be numeric) and email (valid format).
Better error handling for invalid inputs.
Save and load functionality to persist contacts across sessions.
This code demonstrates fundamental concepts in Python, such as dictionaries, loops, conditionals, and input handling, making it a great beginner project for understanding how to build interactive applications.
