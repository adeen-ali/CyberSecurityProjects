# Cryptography Project

This is a simple Python project that demonstrates how to encrypt and decrypt files using cryptography concepts.

The project uses public and private key pairs to secure a text file. The public key is used for encryption, while the private key is used for decryption.

## Project Description

This project helps beginners understand how file encryption and decryption work using Python. It includes scripts to generate keys, encrypt a file, and decrypt the encrypted file back to its original form.

## Features

- Generate public and private keys
- Encrypt a text file using a public key
- Decrypt an encrypted file using a private key
- Simple hands-on example of cryptography in Python

## Files Included

- `gen_keys.py` - Generates public and private keys
- `encrypt.py` - Encrypts the original file
- `decrypt.py` - Decrypts the encrypted file
- `data.txt` - Original text file
- `data.txt.encrypted` - Encrypted file
- `data.txt.encrypted.decrypted` - Decrypted output file
- `pub.pem` - Public key
- `priv.pem` - Private key

## Requirements

Install the required Python package:

```bash
pip install cryptography
