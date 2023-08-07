# Wheel-of-fortune
a Python project
Project Description: Wheel of Fortune Game

This project presents a simplified version of the classic game "Wheel of Fortune." The computer selects a random word from a list of words, and the user attempts to guess the letters in the word until they complete it or make five incorrect guesses.

Key Features:

Word Selection: The program has a predefined list of valid words. It randomly chooses a word from the list for each game session.
Display Representation: The program provides a visual representation of the word using underscores, indicating the number of letters in the word. This representation helps the user better understand the word's structure.
Letter Guessing: The user is prompted to guess a letter (a-z) throughout the game. The program ensures that the input is a single alphabetical character and handles invalid inputs appropriately.
Updating Word Representation: When the user correctly guesses a letter present in the chosen word, the program updates the word representation to reveal the correctly guessed letters.
Tracking Used Letters: The program maintains a list of used letters to avoid repetition and display the previously guessed letters.
Winning and Losing Conditions: The game continues until the user successfully guesses all the letters in the word or reaches five incorrect guesses. In either case, the program informs the user of the outcome.
