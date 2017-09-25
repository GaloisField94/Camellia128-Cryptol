# Camellia128-Cryptol
Camellia128 cipher in Cryptol language

Note: as today (25-09-2017) encryption and decryption for 128-bit key works.
Encryption for 192/256 gives very strange results: first 16 bits match but the rest does not. Decrypting a ciphertext given by encryption gives back a correct plaintext.
