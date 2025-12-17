# Snake Game

A classic Snake game implemented in Python using the Pygame library. This version supports multiplayer gameplay with two snakes competing on the same board.

## Features

- Multiplayer support (up to 2 players)
- Smooth gameplay with sprite-based graphics
- Sound effects and background music
- Score tracking
- Customizable game board size and scale

## Installation

1. Ensure you have Python 3.13 or higher installed.
2. Clone or download this repository.
3. Install dependencies using `uv`:

```bash
uv sync
```

## Usage

Run the game with:

```bash
uv run main.py
```

### Controls

- **Player 1 (Blue Snake)**: Arrow keys (Up, Down, Left, Right)
- **Player 2 (Red Snake)**: WASD keys (W, S, A, D)

The game starts paused. Press any key to begin.

## Requirements

- Python >= 3.13
- Pygame >= 2.6.1

## Development

This project uses several development tools for code quality:

- **pytest**: For running tests
- **mypy**: For static type checking
- **ruff**: For linting and formatting
- **pydoclint**: For docstring checking

To run tests:

```bash
uv run pytest
```

To check types:

```bash
uv run mypy
```

To lint:

```bash
uv run ruff check
```

## License

[MIT License](LICENSE)

## Contributing

Feel free to submit issues and pull requests.
