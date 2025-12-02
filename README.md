# Hangman_Game
Welcome to the Hangman Game, a classic word-guessing challenge built entirely in Python using a simple and interactive command-line interface (CLI). This project demonstrates core Python fundamentals like loops, conditions, lists, functions, and user input validation.

* Project Overview

This Hangman game randomly selects a hidden word from a predefined list. Players must guess the word one letter at a time, while avoiding too many incorrect guesses. With each wrong attempt, the player moves closer to losing—creating suspense and excitement throughout the gameplay.

* Features

    1) Random word selection
    2) Input validation (letters only, one character at a time)
    3) racks guessed letters
    4) mited number of wrong attempts (6 lives)
    5) Real-time feedback after each guess
    6) Clear win/lose end messages
    7) Beginner-friendly, clean, and readable Python code

* How It Works

    i. The program randomly chooses a word from a list.
    ii. The player guesses letters to reveal the word.
    iii. If the guessed letter is correct, it appears in its position(s).
    iv. Wrong guesses decrease the player's remaining attempts.
    v. The game ends when the player wins (guesses all letters) or loses (runs out of attempts).

* Concepts Used

    * random.choice() for picking words
    * Lists & string manipulation
    * Loops (while)
    * Conditional logic (if-elif-else)
    * Guard clauses for input validation
    * User interaction through CLI
