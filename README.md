# Frog Leap Game

The Frog Leap Game is a console-based Python implementation of a classic puzzle game where the player needs to move frogs and toads to a specific arrangement on a riverbank.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Game Rules](#game-rules)
- [License](#license)

## Installation

1. Make sure you have Python installed on your system. You can download it from [python.org](https://www.python.org/downloads/).

2. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/your-username/frog-leap-game.git
   ```

3. Change into the project directory:

   ```bash
   cd frog-leap-game
   ```

4. Run the game:

   ```bash
   python frog_leap_game.py
   ```

## Usage

- The game will prompt you to input the position of the frog or toad you want to move.
- Enter the position (0 to 6) of the piece you want to move or type 'q' to quit.
- Follow the on-screen instructions to move the frogs and toads to the winning arrangement.
- The game ends when you successfully arrange all the frogs and toads or when you type 'q' to quit.

## File Structure

- `frog_leap_game.py`: The main Python script containing the game logic.
- `initial_positions.txt`: Text file containing the initial positions of frogs ('G') and toads ('B').

## Game Rules

- Frogs ('G') can move to the right.
- Toads ('B') can move to the left.
- You win when the arrangement becomes 'B', 'B', 'B', '-', 'G', 'G', 'G'.
- Type 'q' to quit the game.

## License

This project is licensed under the [MIT License](LICENSE).

