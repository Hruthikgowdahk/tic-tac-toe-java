# Tic Tac Toe Game (Java Console)

This is a simple Tic Tac Toe game implemented in Java using Object-Oriented Programming (OOP).  
It is a **Human vs AI** console game, where the AI makes random valid moves.

---

## 🎮 How to Play

1. The game is played on a 3x3 grid.
2. Player **X** (Human) takes the first turn.
3. You enter the **row** and **column** (0–2) for your move.
4. The **AI (O)** will then make a move automatically.
5. The first player to get 3 marks in a row (horizontally, vertically, or diagonally) wins.
6. If all 9 cells are filled and no one wins, the game is a **draw**.

---

## 🛠 Tech Stack

- Java
- Eclipse IDE
- Git & GitHub

---

## 🧱 Class Structure

- `TicTacToe` – Manages the board and game logic (win/draw checks).
- `Player` – Abstract class for common player properties.
- `HumanPlayer` – Handles user input from console.
- `AiPlayer` – Generates random valid moves for AI.
- `LaunchGame` – Contains the `main` method to start the game.

---

## 🚀 How to Run the Project

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Hruthikgowdahk/tic-tac-toe-java.git
