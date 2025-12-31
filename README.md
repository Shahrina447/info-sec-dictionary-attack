Dictionary Attack on Hashed Password (SHA-256)

This project demonstrates a dictionary attack on a hashed password using the SHA-256 hashing algorithm.
The purpose of this project is to show how weak passwords can be cracked when they exist in a predefined dictionary.
This assignment was completed as part of the Information Security course.

Objective

The main objective of this project is to:

Demonstrate how password hashing works

Perform a dictionary attack without using any database

Highlight the importance of strong and unique passwords

Features

Uses SHA-256 for password hashing

Performs dictionary-based password cracking

No database is used

Simple and readable Python implementation

Educational demonstration of password security weaknesses

How It Works

The user enters a password.

The password is hashed using the SHA-256 algorithm.

The program reads a dictionary file containing common passwords.

Each dictionary word is hashed using the same algorithm.

The generated hashes are compared with the stored hash.

If a match is found, the password is cracked.

If no match is found, an appropriate message is displayed.

Project Structure
info-sec-dictionary-attack/
│
├── dictionary_attack.py
├── wordlist.txt
└── README.md

How to Run the Program

Make sure Python 3 is installed.

Place dictionary_attack.py and wordlist.txt in the same directory.

Open a terminal in the project directory.

Run the following command:

python dictionary_attack.py

Dictionary File

The dictionary file (wordlist.txt) contains a list of commonly used weak passwords.
The dictionary size is kept moderate for demonstration purposes, but the program supports larger wordlists without any modification.

Limitations

The attack only works if the password exists in the dictionary.

Strong and unique passwords cannot be cracked using this method.

Larger wordlists may increase execution time.

Disclaimer

This project is intended for educational purposes only.
It is designed to help understand password security concepts and common attack techniques.

Author

Shahrina Khan
BS Computer Science
University of Management and Technology (UMT)
