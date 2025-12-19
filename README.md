# CIS-7-Case-3-Kazim-Jafri
Case 3 | Vigenere Cipher
# Case 3: Vigenere Cipher Encryption and Decryption

## Project Description
This project implements the Vigenere Cipher using C++ as part of a Discrete Structures Project.
The program encrypts and decrypts a user-provided message using a repeating keyword.
After encryption, the program decrypts the ciphertext to verify that the original message
is recovered correctly.

## Programming Approach
- The program cleans the keyword by removing non-alphabetic characters and converting it to uppercase.
- Alphabetic characters are converted to numerical values (A–Z → 0–25).
- Modular arithmetic is used for encryption and decryption:
  - Encryption: Ei = (Pi + Ki) mod 26
  - Decryption: Di = (Ei - Ki + 26) mod 26
- Non-alphabetic characters such as spaces and punctuation are preserved.
- Original letter casing (uppercase/lowercase) is maintained.

## Author
- Kazim Jafri  

## Date Published
- December 18 2025

## How to Run the Program
1. Open `src/vigenereciphercase3KazimJafri.cpp` in a C++ IDE.
2. Compile and run the program.
3. Enter a message and a keyword when prompted.
4. The program will display:
   - Original message
   - Encrypted message
   - Decrypted message
