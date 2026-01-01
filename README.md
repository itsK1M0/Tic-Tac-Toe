# 🎮 Tic-Tac-Toe Game (Python)

A simple Python-based **Tic-Tac-Toe** game created as part of the **Cisco Python Essentials 1** course.  
The game is played in the terminal, where you compete against the computer in a classic 3×3 grid.

The computer always plays with **`X`** and makes the **first move**, starting from the center of the board.  
You play with **`O`**.

---

## ✨ Features

- **Interactive Gameplay**  
  Turn-based game between the player and the computer

- **Input Validation**  
  Ensures user input is numeric, within range (1–9), and placed on an empty square

- **Visual Board Display**  
  Clear board representation with numbered positions for easy move selection

- **Win Detection**  
  Automatically checks for winning conditions or a tie after each move

- **Random Computer Moves**  
  The computer selects random valid moves (no AI logic)

---

## 🕹️ How to Play

1. The game starts with the computer placing an **`X`** in the center square (position **5**)
2. On your turn, enter a number between **1 and 9** to place your **`O`**
3. The board positions are numbered as follows:

-  1 | 2 | 3
- --+---+--
-  4 | 5 | 6
- --+---+--
-  7 | 8 | 9

--- 


4. The game continues until one of the following conditions is met:
- You place **three `O`s** in a row → **You win**
- The computer places **three `X`s** in a row → **Computer wins**
- All squares are filled with no winner → **Tie**

---

## ▶️ How to Run the Game

### 🛠️ Installation

1. Clone the repository:

```bash
git clone https://github.com/itsK1M0/Tic-Tac-Toe.git
cd Tic-Tac-Toe
```

2. Make sure Python is installed :

```bash
python --version
```

3. Run the game :

```bash
python tic_tac_toe.py
```

---

## 📚 Learning Objectives

This project demonstrates key Python fundamentals learned in Python Essentials 1, including:
- Functions and control flow
- Lists and indexing
- Input handling and validation
- Loops and conditional logic
- Basic game logic implementation

---

## 🎯 Notes

+ This game does not use AI or minimax logic
+ Computer moves are randomly selected from available squares
+ Designed for learning and practice purposes
