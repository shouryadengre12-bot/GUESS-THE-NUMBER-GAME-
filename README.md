# GUESS-THE-NUMBER-GAME-
## Overview
The game allows a user to guess a random number selected by the system between 1 and 100. The objective is to guess the number in the minimum number of tries, using feedback ("too high" or "too low") after each attempt until the correct number is found.

## Features
- Random number generation within a defined range (1-100)
- User input and comparison with the secret number
- Instant feedback ("Too high", "Too low", or "Correct!")
- Looping mechanism continues until the right answer
- Attempt limit (optional extension)
- Attempt counter and summary at the end
- Input validation (non-numeric, out-of-range)
- Personalization (optional: use player’s name)

## Scope & Requirements

### Functional Requirements
- Generate a random secret number
- Take and validate user guesses
- Provide feedback for each guess
- Track number of attempts
- Congratulate user and report attempts upon success

### Non-functional Requirements
- Responsive and immediate feedback
- Simple interface and clear instructions
- Robust input validation and error handling
- Reliable performance without crashes

## Technologies / Tools Used
- Python 3
- `random` module (builtin)
- `input()`, `print()`, error handling (`try`-`except`)

## Steps to Install & Run the Project
1. Save the code in a file named `guess_game.py`.
2. Open terminal/command prompt.
3. Navigate to the directory containing the file.
4. Run the game using:

## Run in Google Colab
https://colab.research.google.com/drive/18dx3_i-uRgT5KHmr79OnBAcezdpyGiBR?usp=sharing
*Use this link to play directly in your browser.

## Instructions for Testing 
- Run the script and play the game.
- Check "Too low", "Too high", and success messages.
- Enter invalid input (text, decimals, etc.) and verify graceful error handling.
- Edge cases: Guess numbers at boundaries (1, 100).

## Implementation & Learnings 
This project uses basic Python constructs in a modular way for gameplay, validation, and user feedback. Key learnings include improving input handling, providing clear feedback, and structuring code for readability and reliability.
