# Java Exercises For Artemis

## Recap

#### Read
- [OOP Concepts](https://www.geeksforgeeks.org/object-oriented-programming-oops-concept-in-java/)
  - no need to read about "Pillars of OOP" 
- [Classes](https://www.geeksforgeeks.org/classes-objects-java/)
- [Methods](https://www.geeksforgeeks.org/methods-in-java/)
- [Strings](https://www.geeksforgeeks.org/strings-in-java/)
- [Lists](https://www.geeksforgeeks.org/arraylist-in-java/)
  - will be needed for the last exercise 

#### Watch
- [thenewboston](https://www.youtube.com/playlist?list=PLFE2CE09D83EE3E28)
  -  videos 14, 15, 16, 38, 39, 40, 46, 47


## Exercises

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
  - add quantity to the product. If the product already exists in the shop, add quantity to the existing product;
  if does not exist, create a new product in the shop.
- allow users to remove products
  - remove some quantity from the product. If the quantity is 0, the product is removed from the shop. 
- allow users query a list of products
  - print information about all the products in the shop 
 
You should divide your program to the following classes:
- `Product`: holding information about a single product.
  - Name of the product
  - Amount of the product 
  - Getters and setters for name and amount
- `Shop`: holding information about the entire shop.
  - List of the products in the shop 
  - Getters and setters for the list
- `Main`: the main program.
  - all the things regarding user interaction  

Interaction with the program will be done via a menu. Options will be displayed to the user, allowing him to select what to do with the program. Example:

```
1. View products
2. Add Product
3. Remove Product
4. Exit
Select: 
```

The user will then enter a number indicating the action to perform. The program will then move to a sub-menu depending on the action.

```
1. View products
2. Add Product
3. Remove Product
4. Exit
Select: 2

Enter Product Name: Whip
Enter Product Quantity: 5
```

Upon finishing work with the sub-menu, the program will return to the main menu.

You do have some freedom to implement things a bit differently, but I do expect at least the minimum described here.
