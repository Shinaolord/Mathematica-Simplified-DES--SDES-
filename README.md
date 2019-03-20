# Simplified-DES--SDES-
Implements Simplified DES, which is a pedagogical tool for understanding modern Fiestel network ciphers and modern cryptographic tehcniques. This version is intentionally broken down into individual functions, in the style of OOP (object-oriented programming), to make understanding the cipher easier.

To encrypt a 12 bit binary string via a 9 bit key, we use the following syntax:

sdes["string","key",rounds,EncryptQ]

Where "rounds" is an integer, string/key are the string to encrypt and key, respectively, and EncryptQ= 1 for encryption, -1 for decryption.
