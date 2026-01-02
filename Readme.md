# 🎰 Python Slot Machine Game

This is a simple **console-based Slot Machine game** built using Python.  
The project was created as a learning exercise to understand **Python basics**, **functions**, **loops**, **dictionaries**, and **randomization**.

---

## 📌 Features

- Deposit money and manage balance
- Choose number of lines to bet on (1–3)
- Set bet amount per line
- Random slot machine spins
- Automatic win checking
- Displays winnings and winning lines
- Keeps running until the user quits

---

## 🛠️ Technologies Used

- **Python 3**
- Built-in `random` module
- No external libraries required

---

## 🎮 How the Game Works

1. The player deposits an initial amount.
2. The player selects:
   - Number of lines to bet on
   - Bet amount per line
3. The slot machine spins randomly.
4. If symbols match across a line:
   - The player wins based on symbol value.
5. Balance updates after every spin.
6. The game continues until the player quits.

---

## 🎲 Slot Symbols & Values

| Symbol | Frequency | Value |
|------|-----------|-------|
| A    | Low        | 5     |
| B    | Medium     | 4     |
| C    | High       | 3     |
| D    | Very High  | 2     |

> Symbols with **lower frequency give higher rewards**.

---

## ▶️ How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
2. Navigate into the project folder:
   ```bash
   cd your-repo-name
3. Run the program:
   ```bash
   python main.py
   ```
