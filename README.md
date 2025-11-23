#                                           <---------------NUMBER GUESSING GAME--------------->


## Description ##


The Number Guessing Game is a simple Python console application where the computer randomly selects a number between 1 and 100, and the player has 10 attempts to guess it correctly. After each guess, the game provides feedback indicating whether the guess is too high or too low, helping the player narrow down the correct answer.

The project demonstrates the use of:

1. Random number generation
2. User input handling
3. Conditional statements
4. Loops
5. Exception handling for invalid inputs

Its purpose is to help beginners practice basic Python programming concepts while building an interactive and fun game.


## Installation ##


```bash
git clone <your-repo-url>
cd <project-folder>
npm install
```

## Output Examples Screenshots ##

1. USER GUESSED IN 6 ATTEMPTS

   ![Output 1](https://github.com/daksh-dua30/Number-Guessing-Game-CSFCP/blob/204def73da8b9c0b13bb7d267f92ef4a3aa6327d/OUTPUT%201.jpg)

2. USER GUESSED IN 3 ATTEMPTS

   ![Output 2](https://github.com/daksh-dua30/Number-Guessing-Game-CSFCP/blob/a6872f3b3a57c01810d69df9418b3814b685d716/OUTPUT%202%20.jpg)

3. USER UNABLE TO GUESS IN 10 ATTEMPTS  

   ![Output 3](https://github.com/daksh-dua30/Number-Guessing-Game-CSFCP/blob/e794c564a430d8f96aea68efcdbc69e188f196c1/OUTPUT%203.jpg)
   

## Features ##


Features of the Number Guessing Game

1. Random Number Generation

The game automatically generates a random number between 1 and 100, ensuring each round is unique and unpredictable.

2. Limited Attempts

Players have 10 attempts to guess the correct number, adding challenge and encouraging strategic thinking.

3. Interactive Hints

After each guess, the game provides helpful hints:

"Too low!" if the guess is smaller than the target

"Too high!" if the guess is larger
These hints guide the player toward the correct answer.

4. Input Validation

The game checks whether the player enters a valid number:

Rejects non-numeric input

Prevents the game from crashing due to invalid entries

5. Error Handling

The program includes try-except blocks to gracefully handle:

ValueError for invalid inputs

KeyboardInterrupt if the user exits using Ctrl + C

Unexpected errors with informative messages

6. Game Over Condition

If the player uses all 10 attempts without guessing correctly, the game reveals the correct number.

7. Simple and User-Friendly

Clear prompts and messages ensure the game is easy to play, even for beginners.

8. Fully Console-Based

Runs directly in the terminal, making it lightweight and compatible with any system that supports Python.


#                                           <---------------THANK YOU!--------------->
