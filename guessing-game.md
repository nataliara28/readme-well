# 🎯 Number Guessing Game

Welcome to the **Number Guessing Game**! Test your guessing skills by trying to identify the secret number between 1 and 100. 

## 📜 Project Overview

This game challenges you to guess a randomly generated number within a certain range. With each incorrect guess, you'll get a hint to help you zero in on the correct number. The game keeps track of how many attempts it takes for you to guess correctly.

### 📝 Features

- **Random Number Generation**: The secret number is randomly selected between 1 and 100.
- **Input Validation**: Ensures that players enter a valid number within the specified range.
- **Hint System**: Provides feedback if the guess is too high or too low.
- **Replayability**: Players can choose to play again after each round.

## 🛠️ How It Works

The game operates in the following steps:

1. **Secret Number Generation**: 
   - The game randomly selects a secret number between 1 and 100.
  
2. **User Guess Input**: 
   - Players are prompted to guess the secret number. The input is validated to ensure it's a number within the range.
  
3. **Feedback**: 
   - If the guess is too low or too high, the game provides feedback, and the player can guess again.
   - If the guess is correct, the game congratulates the player and displays the number of attempts taken.
  
4. **Replay Option**: 
   - After guessing correctly, the player can choose to play again or exit the game.

## 🔧 Code Explanation

### `number_guessing_game()`
- **Purpose**: Manages the core gameplay, including generating the secret number, receiving user guesses, providing feedback, and tracking attempts.
- **Main Steps**:
  1. Generate a random secret number.
  2. Prompt the user to guess the number.
  3. Validate the input and provide feedback.
  4. End the game when the correct number is guessed.

### `play_game()`
- **Purpose**: Controls the flow of the game, including starting new games and handling the replay option.
- **Functionality**:
  - Calls the `number_guessing_game()` function.
  - Asks the player if they want to play again after each round.
  - Exits the game loop if the player chooses not to play again.

## 🚀 Getting Started

To play the game on your local machine:

1. **Clone the repository** (if applicable) or copy the script into your local environment.
2. **Run the script** using Python:
    ```bash
    python guessing_game.py
    ```
3. Follow the prompts to guess the secret number and enjoy the game!

## 🎮 Gameplay Example

```text
Welcome to the Number Guessing Game!
Guess the secret number between 1 and 100: 45
Too low! Try again!
Guess the secret number between 1 and 100: 75
Too high! Try again!
Guess the secret number between 1 and 100: 60
Congrats! You guessed the number in 3 tries!
Do you want to play again? (yes/no): no
Thanks for playing! Goodbye!
