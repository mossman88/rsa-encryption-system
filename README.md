# rsa-encryption-system# RSA Encryption/Decryption System (C++ Implementation Without Cryptographic Libraries)

This project implements a basic RSA encryption and decryption system using C++, following the assignment requirement to avoid any external cryptographic libraries. It demonstrates how RSA works internally using Euclidean algorithms, modular arithmetic, and simple file handling.

---

 Features

- Accepts prime numbers `p` and `q` (≤ 1000) as input.
- Accepts plaintext as a **string** (e.g., "hello").
- Generates public and private keys manually.
- Encrypts each character in the plaintext.
- Saves encrypted ciphertext and public key (`n`, `e`) to a file.
- Reads from the file and performs decryption.
- Recovers the original plaintext using factorization and modular inverse.

---

 Sample Run

```bash
Enter prime number p (<= 1000): 61
Enter prime number q (<= 1000): 53
Enter plaintext (e.g., 'hello'): hello

Encrypted ciphertext saved to file.

Read from file:
Ciphertext: 2182 2148 1089 1089 2561 
n: 3233, e: 17
Decrypted plaintext: hello
