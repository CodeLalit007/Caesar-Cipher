# Caesar Cipher

## History and usage


The _Caesar Cipher_ was named after Julius Caesar (100 B.C. – 44 B.C). He would use the cipher for secret communication (protect messages of military significance). The Caesar Cipher is a **substitution cipher**. Originally, Julius Caesar would use a shift of three to encrypt/decrypt a message.


## Working
The transformation can be represented by aligning two alphabets
The cipher alphabet is the plain alphabet rotated left or right by some number of positions. For instance, here is a Caesar cipher using a left rotation of three places, equivalent to a right shift of 23 (the shift parameter is used as the key).


## Maths behind this

1. Can be represented using modular arithmetic
2. Assume that : A=0, B=1, C=2, ...., Z=25
3. Encryption process can be represented as : e(x) = (x+k) (mod 26)
4. such that :
    x -> The plain text
    k -> The number of shift (offset)
    26 -> There are 26 letters in the alphabets.


## Example
1. BROWN -> EURZQ
2. DOG -> GRJ
3. JUMPS -> MXPSV

_Note : Here the key(encrypt number) is taken 3_


## Summary

1. Considerably easy to break.
2. Brute force attacks works pretty well due to relatively small keys (only allows 26 different keys).
3. Also known as monoalphabetic cipher, which the same plain text letters are always replaced by the same cipher text letters.
4. Mono - means one, indicates that each letter has a single substitute.
