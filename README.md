# Python Slots Machine Game

Welcome to the Python Slots Game! This is a simple command-line based slot machine game implemented in Python.

## Features

- Simple and intuitive gameplay
- Randomly generated slot machine symbols
- Different payouts based on the symbols matched
- Keeps track of player's balance

## How to Play

1. **Starting Balance**: You start with a balance of ₨.100.
2. **Placing Bets**: You will be prompted to place your bet amount. Enter a valid positive number.
3. **Spinning the Slots**: The slot machine will spin and display a row of three symbols.
4. **Winning and Losing**:
   - If all three symbols match, you win a payout based on the symbol.
   - If the symbols do not match, you lose the bet amount.
5. **Payouts**:
   - 😎: 2x your bet
   - 💀: 4x your bet
   - 😁: 6x your bet
   - 👻: 8x your bet
   - ⭐: 10x your bet
6. **Continue Playing**: After each round, you can choose to play again or quit the game.

## Getting Started

### Prerequisites

- Python 3.x

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/python-slots-game.git
   ```
2. Navigate to the project directory:
   ```bash
   cd python-slots-game
   ```

### Running the Game

Run the game by executing the following command:
```bash
python main.py
```

### Gameplay

1. Follow the on-screen instructions to place your bet and spin the slots.
2. The game will display the result of the spin and update your balance.
3. You can choose to continue playing or quit the game at any point.

## Example

```
..........................
Welcome to Python Slots :)
Symbols: 😎 💀 😁 👻 ⭐
..........................

Current balance: ₨.100
Place your bet amount: 10
Spinning....

.............
😁 | 😁 | 😁
.............

You won ₨.60
Do you want to spin again? (Y/N): N
.......................................
GAME OVER! Your final balance is ₨.150
.......................................
```
