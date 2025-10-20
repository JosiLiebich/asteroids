# Asteroids Game

A classic Asteroids arcade game implementation built with Python and Pygame.

## Description

This is a recreation of the classic Asteroids arcade game where you pilot a spaceship through an asteroid field. Your objective is to survive as long as possible by destroying incoming asteroids while avoiding collisions.

## Features

- **Classic Gameplay**: Navigate your ship and shoot asteroids in a retro arcade experience
- **Asteroid Splitting**: Large asteroids break into smaller pieces when shot
- **Continuous Spawning**: Asteroids continuously spawn from the edges of the screen
- **Smooth Controls**: Rotate, thrust, and shoot with responsive keyboard controls
- **Collision Detection**: Circle-based collision system for accurate hit detection

## Requirements

- Python >= 3.13
- Pygame 2.6.1

## Installation

This project uses `uv` for dependency management. If you don't have `uv` installed, visit [uv documentation](https://github.com/astral-sh/uv) for installation instructions.

1. Clone the repository:

```bash
git clone <repository-url>
cd asteroids
```

2. Install dependencies:

```bash
uv sync
```

## How to Play

Run the game with:

```bash
uv run python main.py
```

### Controls

- **W** - Move forward (thrust)
- **S** - Move backward
- **A** - Rotate left
- **D** - Rotate right
- **SPACE** - Shoot

### Gameplay

- Destroy asteroids by shooting them
- Large asteroids split into smaller ones when hit
- Avoid colliding with asteroids - one hit and it's game over!
- Asteroids spawn continuously from the edges of the screen

## Project Structure

```
asteroids/
├── main.py           # Game entry point and main loop
├── player.py         # Player ship class with controls
├── asteroid.py       # Asteroid class with splitting logic
├── shot.py           # Projectile class
├── asteroidfield.py  # Manages asteroid spawning
├── circleshape.py    # Base class for circular game objects
├── constants.py      # Game configuration and constants
└── pyproject.toml    # Project dependencies
```
