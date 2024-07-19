# Snake Game

This is a classic Snake game implemented using Pygame in Python. The objective is to eat the food, grow the snake, and avoid collisions with the walls or the snake's own body. The game includes levels that increase in difficulty as you progress.

## Features

- **Classic Snake Game**: Navigate the snake to eat food and grow longer.
- **Levels and Scoring**: Score points for each food item eaten. Every 5 points, the level increases, and the snake's speed increases.
- **Pause and Resume**: Pause the game anytime by pressing `P` and resume by pressing `P` again.
- **Game Over Screen**: Displays a message when the game is over, with options to quit or restart.

## Controls

- **Arrow Keys (or W, A, S, D)**: Move the snake in the desired direction.
- **P**: Pause/Resume the game.
- **Q**: Quit the game from the game over screen.
- **C**: Restart the game from the game over screen.

## Requirements

- **Python 3.6+**
- **Pygame**

## Installation

1. **Clone the repository**:
    ```sh
    git clone <https://github.com/ShreyasGowda28/Snake-Game.git>
    cd <Snake-Game>
    ```

2. **Install Pygame**:
    ```sh
    pip install pygame
    ```

3. **Run the game**:
    ```sh
    python snake_game.py
    ```

## Code Overview

- **Colors**: Defined using RGB values for the game elements.
- **Display**: Set up the game window dimensions and title.
- **Snake**: The snake is represented as a list of blocks.
- **Fonts**: Used for displaying messages and scores.
- **Functions**:
  - `our_snake()`: Draws the snake on the screen.
  - `message()`: Displays messages on the screen.
  - `gameLoop()`: Main game loop handling game logic, events, and rendering.

## How to Play

- Use the arrow keys or `W`, `A`, `S`, `D` to move the snake.
- Eat the red food to grow longer and score points.
- Avoid hitting the walls or the snake's own body.
- Press `P` to pause or resume the game.
- Press `Q` to quit the game or `C` to restart after a game over.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Enjoy playing the Snake Game! If you encounter any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

---
