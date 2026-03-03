# Snake Game

A simple, classic Snake game implemented in Python using the `turtle` graphics module. This lightweight project is designed for learning basic game loops, object-oriented Python, and simple user input handling.

## Features

- Classic snake movement and growth when eating food
- Score tracking and high-score persistence
- Clean, modular code separated into small classes/files for learning and extension

## Requirements

- Python 3.8+ (3.10+ recommended)
- Standard library only (uses `turtle`)

## Installation

1. Clone the repository:

   git clone https://github.com/yourname/snake-game.git
   cd snake-game

2. (Optional) Create and activate a virtual environment:

   python -m venv venv

   # Windows

   venv\Scripts\activate

   # macOS / Linux

   source venv/bin/activate

3. Run the game:

   python main.py

## How to Play

- Use the arrow keys to control the snake: Up, Down, Left, Right.
- Eat the food to grow and earn points.
- Avoid colliding with the walls or the snake's own body.
- The current score and high score are shown at the top.

## Project Structure

- `main.py` — Game entry point and main loop.
- `snake.py` — `Snake` class: manages segments, movement, and collision checks.
- `food.py` — `Food` class: places food randomly on the screen.
- `scoreboard.py` — `Scoreboard` class: displays and persists scores.
- `README.md` — This file.

## Customization & Development

- Change speed, window size, or colors by editing `main.py` and the classes in the module files.
- Add features such as levels, walls, or power-ups to practice extending the codebase.

## Contributing

Contributions, issues, and feature requests are welcome. Feel free to open a pull request or an issue on the repository.

Enjoy!
