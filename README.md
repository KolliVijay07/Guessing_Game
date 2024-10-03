### Guessing Game using Python

This is a simple Python number-guessing game where the player tries to guess a randomly generated number between 1 and 10 within a limited number of attempts based on their chosen difficulty level (Easy, Medium, or Hard).

## Description:

1. **Importing `random` module:**
   - The program uses the `random.randint()` function to generate a random number between 1 and 10 that the player needs to guess.

2. **Player Input and Level Selection:**
   - The player is first asked for their name.
   - The game then prompts the player to choose a difficulty level: `Easy`, `Medium`, or `Hard`. This determines the number of attempts the player has to guess the number.
     - **Easy:** 7 attempts
     - **Medium:** 5 attempts
     - **Hard:** 3 attempts

3. **Game Loop:**
   - Based on the selected difficulty level, the player has to guess the number within the specified number of attempts.
   - Each time the player guesses, the program compares the guess to the randomly generated number and provides feedback:
     - If the guess is too low, it prints "Your guess is too low."
     - If the guess is too high, it prints "Your guess is too high."
   - If the guess is correct, the loop breaks and congratulates the player for guessing the number within the allowed attempts.
   - If the player is unable to guess the number within the allotted attempts, the game ends, revealing the correct number.

4. **End of Game:**
   - The program displays whether the player won by guessing the number correctly or lost by failing to guess the number within the allowed attempts.

### How to Run:

1. Clone the repository or copy the script to your local environment.
2. Run the script in a Python environment.
3. The player will be prompted to enter their name and choose a difficulty level.
4. The game begins, and the player can start guessing the number.

### Example Interaction:

```
Hey player! What's your name: Alice
okay Alice! Let's begin our game
Choose the level (Easy/Medium/Hard): Easy
You have selected EASY level - so guess the number in 7 attempts
I'm going to guess a number between 1 and 10
3
Your guess is too low
5
Your guess is too high
4
You guessed the number in 3 tries!
```

### Note:
The random number generation uses Python's `random` module, ensuring that the number is different each time the game is played.
