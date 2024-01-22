# Automated-SHA-256-Password-Cracking

Overview
This repository contains a simple Python script for automating SHA-256 hash cracking using a brute-force approach. The script uses a provided SHA-256 hash and compares it against a list of passwords from the "rockyou.txt" file.

Usage
Ensure you have the necessary dependencies installed:

bash
Copy code
pip install -r requirements.txt
Run the script with the SHA-256 hash as a command-line argument:

bash
Copy code
python sha256_crack.py <sha256sum>
Replace <sha256sum> with the SHA-256 hash you want to crack.

Disclaimer
This tool is intended for educational and ethical use only. Unauthorized use is prohibited, and the developers are not responsible for any misuse or damage caused by this script.

Dependencies
pwntools: A CTF framework and exploit development library.
Contributing
Feel free to contribute by opening issues or creating pull requests. Ensure that your contributions adhere to the project's coding standards.

License
