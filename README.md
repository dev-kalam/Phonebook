Phonebook Management System

Overview

The Phonebook Management System is a console-based C application designed to store and manage contact information. The application allows users to:

Add new contact entries.

Remove existing contacts.

Search for contacts by name or phone number.

View detailed contact information.

This project is a great demonstration of fundamental programming concepts such as arrays, functions, and basic data structures.

Features

Add Contact: Save a person's name, phone number, address, and email to the phonebook.

Remove Contact: Delete a contact by its name.

Search Contact: Look up contacts by name or phone number.

Prevent Duplicates: Ensure no duplicate names or phone numbers are added.

How It Works

The application uses a fixed-size array to simulate a stack for storing contact information.

Functions are used to perform operations like adding, removing, and searching contacts.

Prerequisites

To run this project, you need:

A C compiler (e.g., GCC or MinGW).

A terminal or IDE to compile and execute the code.

Installation and Usage

Clone this repository:

git clone https://github.com/yourusername/phonebook-management-system.git

Navigate to the project directory:

cd phonebook-management-system

Compile the code:

gcc phonebook.c -o phonebook

Run the program:

./phonebook

Project Structure

phonebook.c: The main source code file containing the application logic.

Usage Instructions

Main Menu:

The program begins with a menu offering options to add, remove, search, or exit.

Adding Contacts:

Enter the contact details as prompted.

Ensure the name and phone number are unique.

Removing Contacts:

Enter the name of the contact to remove.

Searching Contacts:

Choose to search by name or phone number.

The program displays matching contacts.

Exiting:

Select the 0 option to exit the program.

Known Issues

The program does not currently handle overflow or underflow for the stack properly.

Limited input validation is implemented for names, phone numbers, and other details.

Contributing

Contributions are welcome! Please fork the repository, make your changes, and submit a pull request.

License

This project is open-source and available under the MIT License.

Acknowledgements

Thanks to everyone who helped in building and testing this project.

