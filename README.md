# LoginPortal
 LogIn portal

Welcome to the early beta release of my project—a secure login portal emphasizing password security for workers. This initial version sets the foundation for managing worker profiles and ensuring robust authentication practices.

Key Features:
Username and Password Validation: Utilizes stringent validation criteria to ensure strong password policies.
Manager Control: Allows managers to oversee and edit worker profiles, ensuring operational efficiency.
Default Manager Setup: Includes a default manager profile for initial setup and management.
Future Updates: Look forward to upcoming releases that will introduce advanced features like file encryption using asymmetric encryption techniques. This will bolster project security by safeguarding shared files within the workplace.

I appreciate your interest and feedback as we continue to enhance and expand this project.

## Instructions

When first starting off this program I created a default manager login. This is meant as a first time manager to sign in, create their account and delete the default manager.

Credentials for default manager are as follows (this can be changed yourself by editing the code):
Username: OpeningMana!ger5634
Password: sDasvf43#DSa32

In order for new workers to sign up they require a special key, this can only be created by the manager. Once a key is used it is stored in the used_key dictionary and cannot be used again.

## Installation

1. Clone the Repository.

git clone https://github.com/KeanuGhal/LoginPortal/blob/main/LogInScreen

2. Navigate to the Project Directory

cd your-repository

3. Run the Program:
Execute your program.

python main.py

## Usage

Program Usage
This program serves as an early beta version of a secure login portal designed for managing worker profiles with enhanced password security measures. It emphasizes the importance of strong password practices among employees. Currently, the program allows for:

New Sign-In: Enables new employees to register with validated usernames and secure passwords.
Existing User Sign-In: Allows registered employees to log in securely using their credentials.
Manager Sign-In: Grants managers access to administrative functions such as managing worker profiles.
Manager Features: Includes functionalities for creating new manager profiles, editing worker profiles, listing current workers, and removing workers.
Future updates aim to implement file encryption using asymmetric encryption techniques, further enhancing project security within the workplace.

## Credits

BTCInput: A utility for handling robust user inputs in Python.

Credits: Created by John Zelle, as part of the "Python Programming: An Introduction to Computer Science" textbook.
GitHub Repository: BTCInput
pickle: Python's built-in serialization module used for saving and loading Python objects to and from files.

Credits: Developed as part of the Python standard library.
os: Python's built-in library for interacting with the operating system, providing functions to work with files and directories.

Credits: Developed as part of the Python standard library.
time: Python's built-in module providing various time-related functions.

Credits: Developed as part of the Python standard library.
random: Python's built-in module for generating pseudo-random numbers and performing random selections.

Credits: Developed as part of the Python standard library.
string: Python's built-in module providing string-related functions and constants.

Credits: Developed as part of the Python standard library.
secrets: Python's built-in module for generating secure random numbers suitable for managing data such as passwords, account authentication, and security tokens.

Credits: Developed as part of the Python standard library.
These libraries contribute essential functionalities to your project, ensuring robust input handling, data persistence, file system interaction, time management, and security-related operations.

## License

MIT License

Copyright (c) 2024 Keanu Ghaliaei

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
