# Number Guessing Game

A robust command-line interface (CLI) game developed in Python. This project was built as part of the [roadmap.sh](https://roadmap.sh/backend) Backend Developer learning path to practice fundamental programming concepts, input validation, and project structure. The original link of the project is: https://roadmap.sh/projects/number-guessing-game

## Features

- **Difficulty Levels**: Three preset modes (Easy, Medium, Hard) with varying attempt limits.
- **Input Validation**: Implements error handling to prevent application crashes when non-numeric characters are entered.
- **Clue System**: Users can request a hint (Even/Odd) by entering '0', limited to once per round.
- **Interactive Gameplay**: Real-time feedback on whether the target number is higher or lower than the current guess.
- **Penalty Logic**: Inputs outside the valid range (1-100) result in a lost attempt as a penalty.

## Technical Implementation

- **Language**: Python 3.12+
- **Modules**: `random` for secret number generation and `time` for improved user experience.
- **Error Handling**: Uses `try-except` blocks to manage `ValueError` exceptions during type conversion.
- **Control Flow**: Utilizes `match-case` statements (Python 3.10+) for difficulty selection and modular functions for clean code.

## How to Run

1. **Clone the repository**:
   ```bash
   git clone [https://github.com/F3F1T0/number-guessing-game.git](https://github.com/F3F1T0/number-guessing-game.git)
