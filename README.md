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

Here is a flowchart that more clearly shows the program flow and logic. Note that it does not contain the step of validating that the guess is valid and repeating the step of prompting the user for a guess if it is not.

![A flowchart containing nine boxes and nine flowlines. A flowline points from the terminal labeled "Start" to the process labeled "Choose random target number", which has a flowline pointing from it to the process "Prompt user for guess", which has a flowline pointing from it to the condition "Target number greater than guess?" which has a flowline labeled "No" pointing from it to the condition "Target number less than guess?" which has a flowline labeled "No" pointing from it to the process "Announce guess is correct" which has a flowline pointing from it to the terminal "End". A flowline labeled "Yes" points from the aforementioned condition "Target number greater than guess?" to the process "Announce target number is more" which has a flowline pointing from it to the aforementioned process "Prompt user for guess". A flowline labeled "Yes" points from the aforementioned condition "Target number less than guess?" to the process "Announce target number is less" which has a flowline pointing from it to the aforementioned process "Prompt user for guess".](https://github.com/user-attachments/assets/a344ca49-bbde-48cb-9461-0d6d1e4f39e6)

Because the flowchart more clearly shows the program flow and logic than the description, it is closer to an actual implementation of the guessing game. Speaking of an actual implementation, [an example implementation](https://samocodingclub.github.io/guessing-game-example) is available for you to try to get an idea of how such an implementation would work. Note that user input validation is done using HTML forms, so you will need to validate the input yourself in your implementation.

## Your turn!

Now it is *your* turn to translate the logic outlined into actual code in whatever language you choose! If you would like to create this implementation while using a Chromebook, you can use [GitHub Codespaces](https://github.com/codespaces) to do so. When you launch a Codespace it runs on an Ubuntu Linux virtual machine with many popular tools and languages pre-installed for you, so if you are unable to run your program from the terminal, install the relevant package using the `apt-get` (Advanced Package Tool) command.
