# Information Security Project: AES Encryption and Decryption

## Introduction
This project implements the Advanced Encryption Standard (AES) algorithm for encryption and decryption. AES is a symmetric-key encryption algorithm widely used to secure sensitive data. The implementation includes key generation, substitution, permutation, and other operations required for AES encryption and decryption.

## Code Overview
The code consists of Python functions to perform various AES operations:

1. **SubNibbles**: Performs substitution of each nibble in the input using a predefined substitution table.
2. **ShiftRows**: Shifts the rows of the input block cyclically to the left.
3. **MixColumns**: Mixes the columns of the input block according to a predefined matrix.
4. **Inverse MixColumns**: Performs the inverse operation of MixColumns.
5. **GenerateRoundKeys**: Generates round keys from the master key for multiple rounds of encryption.
6. **AddRoundKey**: Adds the round key to the input block.
7. **Encryption**: Encrypts a given text block using AES.
8. **Decryption**: Decrypts a given ciphertext block using AES.
9. **DecryptSecretFile**: Decrypts a file encrypted using AES and writes the decrypted content to another file.

## How to Use
1. Run the `encryption()` function to encrypt a text block.
2. Run the `decryption()` function to decrypt a ciphertext block.
3. Run the `decrypt_secret_file()` function to decrypt a file encrypted using AES.

## Files
- `aes_encryption.py`: Contains the AES encryption and decryption functions.
- `secret.txt`: Sample encrypted file for decryption.
- `plain.txt`: Output file for decrypted content.

## Prerequisites
- Python 3.x
- Knowledge of hexadecimal representation and basic cryptography concepts.

## Notes
- This implementation assumes a 16-bit hexadecimal input for encryption and decryption.
- It uses predefined substitution tables and matrices for various AES operations.

## References
- Advanced Encryption Standard (AES) specification.
- Python documentation for built-in functions and libraries used.

Feel free to explore and modify the code as per your requirements!
