
# Ataxx Project

## Overview
This repository contains my implementation of the Ataxx board game for the UC Berkeley Computer Science course. The project includes a fully functional game engine, AI opponent, and an optional graphical user interface (GUI). Ataxx is a two-player strategy game played on a 7x7 board, with the aim to have the most pieces when no more moves are possible.

## Features
- **Game Engine**: Robust handling of game rules, piece movements, and win conditions.
- **AI Opponent**: A competitive AI capable of making strategic moves and identifying forced wins.
- **Graphical User Interface**: An optional feature that enhances user experience (extra credit component).
- **Command Line Interface**: For those who prefer textual commands, a fully developed CLI is available.
- **Extensive Testing**: Unit and acceptance tests ensure the reliability and correctness of the game logic.

## Installation
To run this project, clone the repository and compile the Java files.
```bash
git clone https://github.com/PeterChoi7/ataxx.git
cd ataxx
javac *.java
```

## Usage
To start the game, run:
```bash
java -ea ataxx.Main
```

For the GUI version, run:
```bash
java -ea ataxx.Main --display
```

## Game Rules
- The game starts with pieces in all four corners.
- Players can either extend or jump with their pieces.
- The goal is to have the most pieces on the board at the end.
- The game ends when no more moves are possible, or a maximum of 25 consecutive jumps have occurred.

For detailed rules and gameplay mechanics, please refer to the `RULES.md` file.

## Contributing
While this project was developed for academic purposes and is not actively maintained, suggestions and improvements are welcome. Please open an issue or a pull request for any contributions.

## Acknowledgements
Special thanks to the UC Berkeley CS faculty for providing guidance and resources throughout this project.
