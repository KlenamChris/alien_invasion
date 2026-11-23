# 👾 Alien Invasion

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Python](https://img.shields.io/badge/Python-3.x-blue)](https://www.python.org/)
[![Package Manager](https://img.shields.io/badge/Package_Manager-uv-6E40C9)](https://docs.astral.sh/uv/)
[![Pygame](https://img.shields.io/badge/Game_Engine-Pygame-green)](https://www.pygame.org/)

**Alien Invasion** is a classic arcade-style shooting game inspired by the iconic *Space Invaders*. Players control a spaceship to defend Earth against waves of alien invaders. The objective is to eliminate all incoming aliens before they reach the player's spaceship.

## Table of Contents

- [Features](#features)
- [Gameplay](#gameplay)
- [Installation](#installation)
- [Usage](#usage)
- [Controls](#controls)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)
- [Acknowledgments](#acknowledgments)

## Features

- Classic arcade-style shooting gameplay.
- Multiple levels with progressively increasing difficulty.
- Score tracking to challenge your high scores.
- Retro-inspired graphics and sound effects.
- Smooth animations and responsive controls.

## Gameplay

- **Objective:** Destroy all alien ships before they reach your spaceship.
- **Movement:** Navigate your spaceship horizontally to avoid incoming threats.
- **Combat:** Shoot lasers to eliminate alien invaders.
- **Difficulty:** The game becomes progressively more challenging as you advance through levels.
- **Lives:** Players start with a limited number of lives. The game ends when all lives are lost.

## Installation

Follow these steps to download and run Alien Invasion locally.

### Prerequisites

Make sure you have the following installed:

- **Python 3:** [Download Python](https://www.python.org/downloads/)
- **uv:** Python package and project manager. [Installation Guide](https://docs.astral.sh/uv/getting-started/installation/).
- **Git:** [Download Git](https://git-scm.com/downloads)

### 1. Clone the repository

```bash
git clone https://github.com/KlenamChris/alien_invasion.git
```

### 2. Navigate to the project directory

```bash
cd alien_invasion
```

### 3. Set up the virtual environment

Create a virtual environment using uv:

```bash
uv venv
```

### 4. Install dependencies

If the project contains a `requirements.txt` file:

```bash
uv pip install -r requirements.txt
```

Alternatively, if the project uses `pyproject.toml` and `uv.lock`:

```bash
uv sync
```

### 5. Run the game

```bash
uv run alien_invasion.py
```

## Usage

Once the installation is complete, launch the game from the project directory:

```bash
uv run alien_invasion.py
```

The game window will open, allowing you to start playing.

## Controls

| Key | Action |
|---|---|
| Left Arrow | Move spaceship left |
| Right Arrow | Move spaceship right |
| Spacebar | Shoot lasers |
| Q | Quit the game |

## Technologies Used

- **Python:** Core programming language used for game logic and application structure.
- **Pygame:** Library used for game development, graphics rendering, sound, and keyboard input handling.
- **uv:** Python package and project manager used for dependency installation and virtual environment management.
- **Graphics and Sound:** Assets used to create the retro arcade experience.

## Contributing

Contributions, suggestions, and improvements are welcome!

To contribute:

1. Fork the repository.
2. Clone your fork:

   ```bash
   git clone https://github.com/YOUR_USERNAME/alien_invasion.git
   ```

3. Navigate into the project directory:

   ```bash
   cd alien_invasion
   ```

4. Create a feature branch:

   ```bash
   git checkout -b feature-name
   ```

5. Install the project dependencies using uv:

   ```bash
   uv venv
   uv pip install -r requirements.txt
   ```

6. Make your changes and test them.
7. Commit your changes:

   ```bash
   git add .
   git commit -m "Add feature"
   ```

8. Push your branch:

   ```bash
   git push origin feature-name
   ```

9. Open a Pull Request against the original repository.

## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

## Contact

**Developer:** Klenam Chris

- **GitHub:** [@KlenamChris](https://github.com/KlenamChris)
- **Repository:** [Alien Invasion](https://github.com/KlenamChris/alien_invasion)

## Acknowledgments

- Inspired by the classic *Space Invaders* arcade game.
- Built with [Python](https://www.python.org/) and [Pygame](https://www.pygame.org/).
- Package management powered by [uv](https://docs.astral.sh/uv/).