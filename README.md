# Password Generator

This script generates random passwords of a specified length, with the option to include symbols and/or uppercase letters.

Usage
To use the script, run the following command:

python PasswordGenarator.ipynb
The script will generate a password with the following default parameters:
* Length: 20 characters
* Symbols: included
* Uppercase letters: included
You can customise the password by providing your own values for the length, symbols, and uppercase arguments:

generating_password(length=10, symbols=True, uppercase=False)
This will generate a password with a length of 10 characters, including symbols, but no uppercase letters.

# Dependencies

This script requires the following modules:
* string: provides a set of string constants that includes all ASCII letters and digits.
* secrets: generates random numbers for the purpose of creating secure tokens.

Notes
* If the symbols and uppercase arguments are both True, the script will print a message indicating that the password will take a long time to crack by a computer.
* If either of the symbols or uppercase arguments are False, the script will print a message indicating that the password will be easier to crack by a computer.

Example Output

Here is an example of the output you might see when running the script:

This password will take million years to crack by computer
4G$@Xfc4$FRYF`=+ANQ7