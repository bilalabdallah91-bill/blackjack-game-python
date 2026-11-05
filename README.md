# 🃏 Blackjack Game (Python Capstone Project)

A command-line implementation of the classic **Blackjack (21)** card game built with Python.

---

## 📌 Project Overview
This project simulates a simplified version of the Blackjack game. The goal is to get a card total as close to 21 as possible without going over, while beating the computer's hand.

### 🌟 Features
- **Dynamic Card Dealing:** Generates random cards from a realistic deck representation.
- **Ace Handling Logic:** Automatically adjusts the Ace value from `11` to `1` if the player's score exceeds 21.
- **Blackjack Detection:** Instantly detects a Blackjack (21 with 2 cards) for both the player and the computer.
- **Interactive Gameplay:** Simple command-line interface with clear emojis and prompt feedback.

---

## 🛠️ Built With
- **Language:** Python 3
- **Modules Used:** `random`, `time`

---

## 🎮 Game Rules Applied
1. The deck has unlimited cards: `[11, 2, 3, 4, 5, 6, 7, 8, 9, 10, 10, 10, 10]`.
2. The Jack/Queen/King all count as `10`.
3. The Ace counts as `11` or `1`.
4. Score of `0` in code represents a true **Blackjack** (Ace + 10-value card).

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone [https://github.com/bilalabdallal/Blackjack-Game.git](https://github.com/bilalabdallal/Blackjack-Game.git)
