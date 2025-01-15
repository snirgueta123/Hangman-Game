# Hangman Game in JavaFX

This is a JavaFX implementation of the classic **Hangman** game. In this game, the player needs to guess a word, one letter at a time. For each incorrect guess, a part of the hangman figure is drawn. The game ends when the player guesses the word correctly or when the hangman figure is fully drawn.

## Features

- **Random Word Selection**: The game picks a random word from a predefined list of words stored in a file.
- **Letter Guessing**: Players can guess letters through clickable buttons. Correct guesses will reveal the letter in the word.
- **Hangman Drawing**: For each incorrect guess, a part of the hangman figure is drawn on a canvas. The game ends when the figure is fully drawn or the word is guessed.
- **Word Progress Display**: The word is displayed with underscores for unguessed letters.
- **Letter Tracking**: The letters the player has already guessed are displayed.
- **Game Reset**: The game can be reset to start a new round with a fresh word.

## Requirements

- Java 8 or later
- JavaFX libraries

## How to Run

1. Clone or download the repository to your local machine.
2. Ensure you have JavaFX installed and properly configured in your environment.
3. Compile and run the project:
    ```bash
    javac HangmanGame.java
    java HangmanGame
    ```
4. Play and guess the word before the hangman is fully drawn!

## Game Interface

- **Word**: Displays the word with missing letters as underscores (`_`).
- **Canvas**: Displays the hangman figure which gets drawn with each incorrect guess.
- **Buttons**: A series of buttons represent the alphabet. Clicking a letter will trigger the guess.
- **Reset Button**: A button to start a new game with a fresh word.

## Game Rules

1. The game starts by selecting a random word from the word list.
2. The player guesses letters, and for every correct guess, the letter is revealed in its correct position.
3. Incorrect guesses cause a part of the hangman figure to be drawn.
4. The game ends when the player successfully guesses all letters of the word or the hangman figure is fully drawn.
5. The player can start a new round by clicking the "New Game" button.


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Happy guessing, and good luck!
