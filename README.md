# 🎲 Mystery Number: Terminal Guessing Game

![Language](https://img.shields.io/badge/Language-Python-FFD43B)
![Interface](https://img.shields.io/badge/Interface-CLI-lightgrey)
![Type](https://img.shields.io/badge/Type-Logic_Minigame-success)

## 🎯 Overview
A lightweight, terminal-based minigame developed in **Python**. This project serves as a practical exercise in control flow, standard I/O handling, and pseudo-random number generation (PRNG).

The objective is simple but strictly constrained: deduce the system's randomly generated integer (between 0 and 20) using a maximum of **3 attempts**.

## 🕹️ Core Mechanics & Rules
- **Pseudo-Random Generation:** At runtime, the system selects a target integer $x$ where $0 \le x \le 20$.
- **Algorithmic Constraint:** The player is limited to a strict execution loop of exactly 3 attempts.
- **Feedback Heuristic:** After each incorrect guess, the game evaluates the input and provides conditional directional feedback (Higher or Lower), encouraging the use of basic *Binary Search* logic to optimize the next guess.
- **Win/Loss State:** The execution loop breaks immediately upon a correct guess (Victory) or reveals the target number if the iteration limit is reached (Defeat).

## 💡 Execution Example

```text
Welcome to the Mystery Number Game!
Try to guess the target integer between 0 and 20.

Attempt 1: 10
> The target number is Higher!

Attempt 2: 15
> The target number is Lower!

Attempt 3: 13
> Congratulations! You've cracked the mystery number!
```

Game Over.
🐍 Requirements
Python 3.x

▶️ How to Play
Ensure you have Python installed on your machine.

Run the script directly from your terminal:
python jogo_misterioso.py

👨‍💻 Coded for fun, logic, and a quick Python warm-up.
