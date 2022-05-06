# Java Exercises For Artemis

#### Binary to Decimal Converter
Write a program to convert a binary number (contained in a `String`, such that each character in the string is either `0` or `1`) to a decimal (as an `int`). Implement the program in 2 parts:
- a method which receives a `String` binary and returns an `int` decimal number
- a `main` which reads a binary number from the user and uses said method to convert the number and display the result returned from it.

Don't use any built-in utilities which already implement the conversion, implement it yourselves. You can read [here](https://www.rapidtables.com/convert/number/binary-to-decimal.html) about how to perform the conversion.

For example: binary `"101"` is equal to decimal `5`.

#### Reverse a String
Write a program which reverses the order of characters in a `String`. Implement the program in 2 parts:
- a method which receives a `String` to reverse, and returns a reversed `String`
- a `main` which reads the `String` from the user and uses said method to reverse the `String` and print the results.

For example: `"This is the greatest plan"` reversed is `"nalp tsetaerg eht si sihT"`.

#### Ceaser Cipher
Write a program capable of encrypting and decrypting `String`s using the [_Ceaser Cipher_](https://en.wikipedia.org/wiki/Caesar_cipher). Implement the cipher in 2 programs - one for encrypting and one for decrypting. Each program will be made up of:
- a method for encrypting or decrypting a `String`.
- a `main` which reads a `String` from the user and uses said method to encrypt or decrypt the `String` and prints the result.

For some explanation of the cipher, read [here](https://www.dcode.fr/caesar-cipher). But basically the idea is that each character is replaced by another character. That character is selected by the cipher, which is basically a _shift_ of the alphabet. So if `shift=2`, we would get that `a = c`. 

Select your own cipher (i.e. shift).

#### Inventory

Create a shop _inventory_ program. This is an OOP project, and you are expected to create classes. The program should:
- keep track of products in the shop
- allow users to add products
- allow users to remove products
- allow users query a list of products

