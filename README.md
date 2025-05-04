# Simple Hangman Game in Python

This is a basic implementation of the classic Hangman game written in Python.

## How to Play

1.  Run the `hangman.py` script using a Python interpreter.
2.  The game will choose a random secret word from a predefined list.
3.  You will be prompted to guess one letter at a time.
4.  Correctly guessed letters will be revealed in the word.
5.  Incorrect guesses will reduce your remaining attempts.
6.  The game ends when you either guess the word correctly or run out of attempts.

## Features

* Random word selection from a list.
* Displays the current state of the word with guessed letters and underscores.
* Tracks the number of incorrect attempts.
* Provides feedback on correct and incorrect guesses.
* Determines and announces the win or loss condition.
* Includes basic input validation to ensure the guess is a single letter.

## Getting Started

1.  **Prerequisites:** You need to have Python installed on your system.
2.  **Download:** Download the `hangman.py` file from this repository.
3.  **Run:** Open a terminal or command prompt, navigate to the directory where you saved the file, and run the script using the command: `python hangman.py` (or `python3 hangman.py` depending on your system).

## Code Structure

* `choose_word()`: This function selects a random word from the `words` list.
* `display_word(secret_word, guessed_letters)`: This function takes the secret word and the set of guessed letters as input and returns a string representing the current state of the word (e.g., "a \_ \_ l e").
* `hangman()`: This is the main function that runs the Hangman game logic, including:
    * Choosing the secret word.
    * Initializing game variables (guessed letters, attempts left).
    * The main game loop that takes user input, checks guesses, updates the display, and manages game state.
* `if __name__ == "__main__":`: This ensures that the `hangman()` function is called only when the script is executed directly.

## Potential Enhancements

* **Visual Hangman:** Add a visual representation of the hangman figure that updates with each incorrect guess.
* **Word Lists from Files:** Allow the game to load word lists from external text files.
* **Difficulty Levels:** Implement difficulty levels by varying the length of the words or the number of allowed attempts.
* **Scorekeeping:** Keep track of the player's score across multiple games.
* **Error Handling:** Add more robust error handling for invalid input.

## Contributing

Feel free to contribute to this project by suggesting improvements or submitting pull requests.

## Author

Durjoy Barua / https://github.com/iamdurjoybarua
