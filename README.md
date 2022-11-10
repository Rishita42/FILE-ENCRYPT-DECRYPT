# FILE-ENCRYPT-DECRYPT

File encryption is a way of encoding files, including the sensitive data they contain, in order to send them securely. The encoding prevents unauthorized access and tampering by malicious actors. It keeps a file from being read by anyone except the person or people for whom it was intended.

Encryption is the act of encoding a message so that only the intended users can see it. We encrypt data because we don’t want anyone to see or access it.
We will use the cryptography library to encrypt a file. The cryptography library uses a symmetric algorithm to encrypt the file. In the symmetric algorithm, we use the same key to encrypt and decrypt the file. 
The fernet module of the cryptography package has inbuilt functions for the generation of the key, encryption of plain text into cipher text, and decryption of cipher text into plain text using the encrypt() and decrypt() methods respectively. The fernet module guarantees that data encrypted using it cannot be further manipulated or read without the key. 
