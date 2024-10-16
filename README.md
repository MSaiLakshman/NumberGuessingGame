#**Number Guessing Game with Time Limit**


**Project Overview**
The Number Guessing Game with Time Limit is a simple console-based game where the player must guess a randomly generated number within a specified range. The player has a limited number of attempts and a time limit to guess the correct number. The game offers two difficulty levels with different ranges and time limits.

Features
The game randomly selects a number within a specified range.
The player can choose between two difficulty levels:
Level 1: Guess a number between 1 and 100, with 10 attempts and a 30-second time limit.
Level 2: Guess a number between 1 and 1000, with 15 attempts and a 60-second time limit.
The game provides feedback on whether the guessed number is too high or too low.
A countdown timer ends the game if the player does not guess the correct number in time.
The player wins if they guess the number correctly within the attempts and time limit.
How to Play
Start the Game: The game prompts the player to select a range for the number guessing (1-100 or 1-1000).
Enter Guesses: The player inputs their guesses, and the game informs whether the number is too high or too low.
Time Limit: The player must guess the number before the time limit expires. If time runs out, the correct answer is displayed, and the game ends.
Win or Lose: The player wins if they guess the number correctly within the available attempts. If they fail, the game reveals the correct answer after the last attempt or when the time runs out.
Requirements
Java installed on your machine.
How to Run the Game
Clone or download the project files to your local machine.
Open a terminal or command prompt in the project directory.
Compile the Java file:

javac NumberGuessingGameTimeLimit.java


Run the game:

java NumberGuessingGameTimeLimit


Example Gameplay
Choose the difficulty level:
Option 1: Guess a number between 1 and 100.
Option 2: Guess a number between 1 and 1000.
Start guessing the number. The game provides hints after each guess, such as:
"Number too low, increase the number."
"Number too high, decrease the number."
Win the game by guessing the correct number or lose by running out of time or attempts.
Contributions
