# TryHackMe: Python: Simple Demo

**Platform:** TryHackMe  
**Room:** Python: Simple Demo  
**Difficulty:** Beginner  
**Status:** Completed

## Overview

I completed the Python: Simple Demo room and built a basic “Guess the Number” game. I learned how to use variables, get input from the user, make decisions with conditional statements, and repeat code with a `while` loop.

## 1. Variables and User Input

I learned how to use variables to store the secret number, the user’s guess, and the number of attempts. The program uses `random.randint(1, 20)` to choose a secret number, `input()` to collect a guess, and `int()` to convert the input from text to a number.

The `print()` function displays messages to the user, and the `tries` variable keeps track of their attempts.

<img width="1920" height="922" alt="1" src="https://github.com/user-attachments/assets/890c21a4-b5b1-4b3d-b9dd-9cd7ec7ec29f" />

**Answers**

- What function displays text on the screen? **`print()`**
- What function converts user input to an integer? **`int()`**

## 2. Conditional Statements

I learned how to use `if`, `elif`, and `else` to compare the user’s guess with the secret number. The program checks whether the guess is outside the range of 1 to 20, too low, too high, or correct.

<img width="1920" height="923" alt="2" src="https://github.com/user-attachments/assets/3a48f1bc-ea84-4a9b-844e-846bf3490385" />

**Answers**

- How does Python write “else if”? **`elif`**
- What will the program display if the user enters `50`? **`That number is out of range. Try again.`**

## 3. Iterations

I learned that loops let a program repeat a block of code while a condition remains true. The game uses a `while` loop to keep asking for guesses until the user enters the secret number. Each guess increments the `tries` counter.

<img width="1920" height="917" alt="3" src="https://github.com/user-attachments/assets/ceedf220-9164-450b-882d-b42b40df6380" />

**Answers**

- What type of loop does the program use? **`while`**
- What will the program display if the user guesses correctly in 3 tries? **`You got it in 3 tries!`**

## 4. Key Takeaways

The main concepts I learned were:

- Variables store values the program needs to use.
- `input()` collects text from the user, and `int()` converts it to an integer.
- `if`, `elif`, and `else` let a program choose what to do based on conditions.
- A `while` loop repeats code until its condition is false.
- A counter such as `tries` can track how many times an action happens.

## 5. Conclusion

Overall, I found this room a helpful introduction to Python. Building the guessing game gave me practice combining variables, user input, conditional statements, and loops in one program.

**Room status:** Completed
