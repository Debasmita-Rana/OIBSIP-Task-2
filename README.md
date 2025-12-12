# OIBSIP-Task-2
Number Guessing Game (Java Console)

This is a classic console-based "Guess the Number" game developed in Java. The application challenges the user to guess a randomly generated secret number within a defined range and a limited number of attempts. It incorporates a comprehensive scoring system and multiple rounds to enhance replayability and challenge.

Features

Customizable Range: The secret number is generated between 1 and 100 (easily customizable via constants).

Limited Attempts: Users are restricted to 7 attempts per round.

Multi-Round Play: The game consists of 3 rounds, tracking success across the entire session.

Interactive Hints: The system provides feedback to the user, indicating whether their guess is HIGHER or LOWER than the secret number.

Dynamic Scoring: Points are awarded based on efficiency. A base score (10 points) plus bonus points (5 points per remaining attempt) are awarded upon a correct guess.

Robust Input Handling: Utilizes try-catch blocks and InputMismatchException handling to prevent crashes from invalid (non-numeric) user input.

Final Score Summary: Displays a final summary including total rounds played, rounds won, and overall total score.
