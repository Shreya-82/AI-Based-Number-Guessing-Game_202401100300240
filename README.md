# AI-Based-Number-Guessing-Game_202401100300240
Overview
This is a Python-based Number Guessing Game where the AI attempts to guess the number you're thinking of, between 1 and 100. The game utilizes a simple guessing strategy, where the AI adjusts its guesses based on feedback provided by the game itself, aiming to correctly guess the number in the fewest possible attempts.

Features
AI Guessing: The AI guesses your number by randomly selecting values within the current range.
Interactive Feedback: After each guess, the AI adjusts its guess based on whether the guess is too high or too low.
Text-Based Interface: The game runs in the terminal or command prompt.

Requirements
Python 3.x (No external libraries are required)

How to Play
When the game starts, the AI will randomly guess a number between 1 and 100.
After each guess, the AI will print whether the guess is too low, too high, or correct.
If the guess is too low, the AI will increase its guess range.
If the guess is too high, the AI will reduce its guess range.
The game continues until the AI correctly guesses the number.

Code Explanation
Randomized Guesses: The AI generates random guesses within the current range, updating the range based on the feedback.
Game Flow:
Too Low: If the AI's guess is lower than the target number, the range is updated, and the AI guesses again.
Too High: If the AI's guess is higher than the target number, the range is updated, and the AI guesses again.
Correct Guess: The game ends when the AI guesses the number correctly, and it reports how many attempts it took.
