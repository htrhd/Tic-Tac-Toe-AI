# Tic Tac Toe AI (Minimax)

A polished Tic Tac Toe game built with **Python** and **Pygame**. This project features a fully unbeatable AI powered by the **Minimax Algorithm**, as well as a casual mode for playing against a friend or a randomized AI.

## 🕹️ Game Features
- **Unbeatable AI:** Level 1 uses Minimax to calculate every possible outcome.
- **Random AI:** Level 0 makes moves randomly for casual play.
- **PvP Mode:** Local multiplayer mode to play against a friend.
- **Visual Feedback:** Clean rendering of win lines and game states.

## ⌨️ Controls
| Key | Action |
| :--- | :--- |
| **Mouse Click** | Place your mark (X or O) |
| **G** | Toggle Gamemode (AI vs. PvP) |
| **R** | Restart/Reset Game |
| **1** | Set AI to Random (Level 0) |
| **2** | Set AI to Minimax (Level 1) |

## 🧠 The Minimax Algorithm
The AI uses a recursive Minimax algorithm to explore the game tree. It assigns values to game states (+1 for a win, -1 for a loss, 0 for a draw) and always chooses the move that minimizes the maximum possible loss, making it impossible to beat when set to Level 1.



## 🚀 Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/htrhd/Tic-Tac-Toe-AI.git](https://github.com/htrhd/Tic-Tac-Toe-AI.git)
   ```

2. **Install dependencies:**
   ```bash
   pip install pygame numpy
   ```

3. **Run the game:**
   ```bash
   python TicTacToe.py
   ```

## 📂 Project Structure
- `TicTacToe.py`: Main game loop, AI logic, and Pygame rendering.
- `constants.py`: Game configurations (colors, sizes, and dimensions).
- `requirements.txt`: Required Python libraries.

---
*Created as a Python learning project focusing on Game Theory and AI.*
