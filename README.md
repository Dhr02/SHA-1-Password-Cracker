SHA-1 Password Cracker

Description:
This project is a simple SHA-1 password cracking tool that attempts to recover plaintext passwords from their hashed values. It uses a dictionary-based attack with an optional salting mechanism to increase effectiveness against salted hashes.

Features:
- Reads a list of common passwords from "top-10000-passwords.txt".
- Hashes each password using SHA-1 and compares it to the given hash.
- Supports cracking salted hashes by reading known salts from "known-salts.txt".
- Tests both prepended and appended salt variations.
- Returns the plaintext password if found; otherwise, returns "PASSWORD NOT IN DATABASE".

Usage:
- Provide an SHA-1 hash as input.
- Specify whether to use known salts.
- The program searches the dictionary and returns the cracked password if available.

Dependencies:
- Python 3
- hashlib (built-in module)

