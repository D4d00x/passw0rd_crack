# Password Cracker

Password Cracker is a Python script that attempts to crack hashed passwords using a dictionary attack.

## Usage

1. Clone the repository:

git clone https://github.com/D4d00x/password-cracker.git


2. Navigate to the project directory:

cd password-cracker


3. Create a dictionary file (`dictionary.txt`) containing a list of words to use for the dictionary attack.

4. Create a password file (`passwords.txt`) containing hashed passwords in the format `<username>:<hashed_password>`.

5. Run the script:

python password_cracker.py


6. The script will read each line from the password file, extract the username and hashed password, and attempt to crack the password using the dictionary attack. If a matching password is found, it will be displayed.

## Example

Suppose you have a password file `passwords.txt` with the following content:

user1:$6$D0A5eM.I$C7pF0PCYW40oNxcpbd.MBih0H7wZyMC4b0pHjHfU06J2I1vEbxk7ZTsn.IYQ51pzoEXvrVvRj1UmRSGDw8I1w.
user2:$6$f9xIsxZk$vp/b5/X1No/y.G1sD3hukKhbV3jSzTz9AZZ3F1ryu37hmkPmE7KTPVVYsJ.jTzI5IAGr6S6xjkt0NAn9vU7xy/


Running the script will output:

[*] Cracking Password For: user1
[+] Found Password: password123

[*] Cracking Password For: user2
[-] Password Not Found.


## Disclaimer

This script is intended for educational purposes and should only be used on systems where you have explicit permission to crack passwords. Unauthorized password cracking is illegal and unethical.

## Requirements

- Python 3.x

## Author

Dado Hatipovic @ EC Utbildning/Security Developer






