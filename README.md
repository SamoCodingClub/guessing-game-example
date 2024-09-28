How to make a guessing game in your favorite programming language
===

This is **not** a tutorial on how to code. There are plenty of great resources online (such as [W3Schools](https://www.w3schools.com)) for learning how to code! This is rather an example of the thought process you might go through when coding, so you can learn to think like a programmer.

Everything is instructions and logic when coding. You write instructions for the computer to execute, and the computer uses rules and logic to execute your program. A programming language is what your instructions are written in. It is generally recommended to start with a "high-level" language as they are more user-friendly.

## The objective

Your objective is to create a program that plays the higher-or-lower guessing game with the user. In order to do so, the program performs the following objectives:
1. The program chooses a random whole number between 1 and an arbitrary upper bound such as 1,000 inclusive.
2. The program prompts the user to input a guess for which of the possible numbers the program chose, prompting the user to guess again if the input is invalid.
3. If the user's guess was incorrect, the program outputs whether the number was greater or less than the user's guess and prompts the user to guess again. Otherwise, the program outputs that the guess was correct.

These objectives should be simple to execute since there is no question to exactly how they should be implemented, as the logic the program should execute is exactly the same as these objectives. (For a more complex program, you would need to reason about exactly how to implement the objectives using logic.) They should also be easy to implement as, other than the random generation of the number to be guessed, the program only needs to perform the extremely basic operations of remembering and comparing whole numbers.

**To be continued... Please check back later**

In the meantime, you can check out the [example implementation](https://samocodingclub.github.io/guessing-game-example). Note that user input validation is done using HTML forms, so you will need to validate the input yourself in your implementation.
