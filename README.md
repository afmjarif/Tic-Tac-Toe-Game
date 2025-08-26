# Tic-Tac-Toe-Game
This is my final project on my object oriented programming course. It's help me to explain all the topics in this code. 
🎮 Tic Tac Toe Game (Java, Terminal-Based)

A colorful Tic Tac Toe game built in Java, playable directly from the terminal.
Supports Human vs Human and Human vs Computer (Easy/Hard AI with Minimax algorithm).

✨ Features

✅ Two Game Modes

Human vs Human

Human vs Computer

✅ Difficulty Levels

Easy → Computer plays randomly

Hard → Computer uses Minimax AI (unbeatable)

✅ Colored Terminal Output (X = 🔴 Red, O = 🔵 Blue, Board = 🟡 Yellow)

✅ Random Toss to decide who plays first

✅ Score Tracking across multiple rounds

✅ Replay Option (Play again or exit anytime)

🛠️ Tech Stack

Language: Java

Concepts Used:

Object-Oriented Programming (OOP)

Minimax Algorithm (for Hard AI)

ANSI Escape Codes (for terminal colors)

📂 Project Structure
.
├── App.java        # Main class (game loop, AI logic, player input)
├── Board.java      # Handles game board, moves, printing
├── Player.java     # Player details and score
├── Colors.java     # ANSI color codes for styled output

🚀 How to Run

Clone or Download the project.

Open a terminal in the project folder.

Compile the program:

javac App.java


Run the program:

java App


Play the game! 🎉

🎲 Gameplay Demo

Start the game:

🎮 Welcome to Tic Tac Toe!
Choose Mode: 1. Human vs Human  2. Human vs Computer


Example board (after few moves):

Current Board:
X O -
- X -
O - X


Scores shown after each round.

Option to continue or exit after each game.

🧠 AI Working (Hard Mode)

Uses the Minimax Algorithm:

Evaluates all possible moves.

Assigns scores:

+10 → AI win

-10 → Human win

0 → Draw

Picks the move with the highest score.

AI is unbeatable in Hard mode.

📌 Future Improvements

Add GUI version (JavaFX/Swing).

Add sound effects.

Support custom board sizes (4x4, 5x5).

👨‍💻 Author

AFM Jarif
B.Sc. in CSE, Manarat International University

⚡ Enjoy the game and try to beat the AI… if you can 😉
