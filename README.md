# Beale Cipher Encryption and Decryption

This Python script demonstrates the encryption and decryption process using the Beale cipher algorithm. The Beale cipher is applied to a given plaintext and decrypted ciphertext, making use of a key generated from a specified book.

## Code Overview

The script consists of the following main sections:

1. **Key Generation:** Reads a specified book file to generate a key for the Beale cipher. Each unique starting letter of a word in the book is mapped to a three-digit code.

2. **Encryption:** Takes a plaintext sentence and encrypts it using the generated key. The output is a sequence of three-digit codes separated by hyphens.

3. **Decryption:** Takes a pre-encrypted ciphertext and decrypts it back to the original plaintext using the generated key.

## Usage

1. Ensure you have a book file named `book.txt` in the same directory as the script.

2. Run the script:

    ```bash
    python beale_cipher.py
    ```

3. View the generated key, ciphertext, and decrypted plaintext in the console.

## Files

- **book.txt:** The text file containing the book used for key generation. Ensure it is present in the same directory as the script.

## Example

Given the provided `plaintext` and `ciphertext2`, the script demonstrates the encryption and decryption processes.

## Notes

- The generated key is based on the starting letter of each word in the book, mapped to three-digit codes.
- The ciphertext is produced by encoding the plaintext using the generated key.
- The decryption process involves reversing the encoding using the generated key.

Feel free to customize the script and adapt it to your specific needs.


