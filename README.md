# 2048 Game

This repository contains the implementation of the popular game 2048, coded in Python. The game logic, constants, and puzzle functionalities are separated into different modules for better modularity and maintainability.

## Files

- `constants.py`: This file contains all the constants used across the game, including grid size, key mappings, etc.
- `logic.py`: This file handles the core game logic, such as movement and merging of tiles, win/loss conditions, and score calculation.
- `puzzle.py`: This file manages the game board (puzzle) and user interactions, such as key presses and tile spawning.
- `tempCodeRunnerFile.py`: A temporary file generated during code execution in some IDEs, typically used to run snippets of code.
- `__pycache__/`: This folder contains Python bytecode files that are automatically generated when Python modules are imported or compiled. It speeds up the loading of the modules.

## How to Run

1. Clone the repository:
    ```bash
    git clone <repository-url>
    ```

2. Navigate to the project directory:
    ```bash
    cd 2048\ GIT
    ```

3. Run the game:
    ```bash
    python puzzle.py
    ```

## Requirements

- Python 3.11 or higher

## Gameplay

The objective of the game is to slide numbered tiles on a grid to combine them and create a tile with the number 2048. The game ends if no more moves are possible.
