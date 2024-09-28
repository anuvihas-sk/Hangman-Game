# Hangman Game 🕹️

## Overview

**Hangman** is a word-guessing game where the player has to guess a hidden word by suggesting letters within a limited number of attempts. This project implements the classic Hangman game in Python, designed to run in a terminal/command line interface.

## Features

- **Interactive gameplay**: The player can guess letters until they either guess the word or run out of attempts.
- **Random word selection**: Words are randomly chosen from a predefined list or file.
- **Word masking**: The word is represented by underscores (`_`), and correct guesses reveal the corresponding letters.
- **Limited attempts**: The player has a limited number of guesses before they lose.
- **ASCII art for the hangman**: Visual representation of the hanging state as the player makes incorrect guesses.

## Prerequisites

To run the Hangman game, you'll need to have the following installed:

- **Python 3.x**: The game is built in Python and requires Python 3 or higher to run.

You can download and install Python from the [official Python website](https://www.python.org/downloads/).

## How to Run the Game

1. **Clone the repository** or download the game files:
   ```bash
   git clone https://github.com/yourusername/hangman-python-game.git
   ```

2. **Navigate** to the project directory:
   ```bash
   cd hangman-python-game
   ```

3. **Run the game**:
   ```bash
   python hangman.py
   ```

4. **Start playing**! Follow the on-screen instructions to guess the hidden word.

## How to Play

1. The game selects a random word from the predefined word list or file.
2. The word is displayed as underscores (`_`), with each underscore representing an unknown letter.
3. The player inputs one letter at a time to guess the word.
4. If the guessed letter is correct, it is revealed in the word. If it is incorrect, the player loses an attempt.
5. The player has a limited number of incorrect guesses before losing the game (usually 6 incorrect guesses).

### Main Files:
- **`hangman.py`**: This is the core Python script that runs the game.
- **`words.py`**: A text file containing a list of words used in the game. You can modify this list to add your own words.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contributing

Contributions are welcome! Feel free to submit a pull request or open an issue if you find any bugs or have suggestions for new features.

---

**Enjoy the game!** 🎉

---
