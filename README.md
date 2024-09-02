# Dungeon Crawler Procedural Generation Through Genetic Algorithm
## Authors
Ismael Cortez, Nelson Norman
## Project Overview  
A genetic algorithm-based 2D top-down Dungeon Generator that focuses on creating beatable levels for developer reference. It will arrange opponents, a boss, a key, doors, traps, and objects in each level according to constraints inside a txt file that can be runned using PyGame for gameplay.
## Theme  
AI simulating a genetic algorithm for use as a Level Design Assistant.
## Problem Statement
Developing unique and interesting levels, finding interesting mechanics, and gameplay based on the design elements takes time. This AI is an example of how AI can assist developers through level generation by altering its layout based on the given design elements and configurable constraints.
## Technical Solution
The objective is to simulate a method of procedural generation through the use of genetic algorithms based on the set design elements and constraints. The use of genetic algorithms allows us to obtain a variety of levels based on a given genome, represented as a sequence of symbols in a text file.
## Usage
Before proceeding, please ensure that you have Python3, NumPy, SciPy, and Pygame installed on your machine.
If you need to install any of the aforementioned software please follow the guides below:
- [Install Python](https://www.python.org/downloads/)
- [Install NumPy](https://numpy.org/install/)
- [Install SciPy](https://scipy.org/install/)
- [Install Pygame](https://www.pygame.org/wiki/GettingStarted)
### Run
1. In the `src/` directory, run `python dungeon.py`
2. Let the program run for a moment (~30 sec)
3. In the parent directory of `src/` look for the `levels/` directory.
4. Copy the file `last.txt` into `src/game/`.
5. In the `src/game/` directory run `python main.py`.
6. A pop up window should open with the playable level.
### How to Play
- **Movement**: W, A, S, D or Arrow Keys
- **Attack**: Space Bar
- **Switch Weapons** (after acquiring second weapon): X
