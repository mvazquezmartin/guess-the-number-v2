
# Guess The Number Game
![Guess The Number responsives](/assets/Screenshot.png "Guess The Number")

This is a JavaScript class GuessTheNumberGame that implements a simple number guessing game. Players attempt to guess a secret number within a certain range. The game provides feedback on each guess and keeps track of the number of attempts made.


## Features

- **Game Initialization:** Upon initialization, the game sets up necessary elements and initializes the GameManager.
- **Number Input:** Users can input numbers via a numeric keyboard interface.
- **Guess Handling:** Handles user guesses, providing feedback and updating the game UI accordingly.
- **Game Reset:** Allows users to reset the game, clearing previous attempts and resetting the secret number.
- **Audio Feedback:** Provides audio feedback for interactions such as number selection, guessing, and game reset.

## Usage

1. **Initialization:** Create an instance of the `GuessTheNumberGame` class to start the game.

2. **Number Input:** Use the numeric keyboard interface to input guesses.

3. **Guessing:** Click the "Guess" button to submit your guess.

4. **Reset:** Click the "Reset" button to reset the game.


## Example

```js
// Initialize the game
const guessTheNumberInit = new GuessTheNumberGame();

// Ensure the DOM is loaded before initializing the game
document.addEventListener('DOMContentLoaded', () => {
  guessTheNumberInit;
});

```


## Dependencies
- This code assumes the existence of a `GameManager` class.
- Audio files for button clicks: `click-numbers.wav`, `click-btn-guess.wav`, `click-btn-reset.wav`.
- Alert with `SeewtAlert2`
## Installation

1. Clone the repository:

```bash
  git clone https://github.com/mvazquezmartin/guess-the-number-v2.git

```
2. Open index.html in your web browser.    
## License

This project is licensed under the [MIT](https://choosealicense.com/licenses/mit/)

