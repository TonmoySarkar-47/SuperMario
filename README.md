# Super Mario Game

## Overview
The Super Mario Game is a 2D platformer built using C++ with OpenGL and GLUT, featuring smooth character movement, obstacle interactions, and a dynamic camera system. Players navigate through levels, collect coins, and avoid obstacles to reach the final goal.

## Installation

To run the Super Mario game, you will need to have the following software installed:

- C++ compiler (e.g., GCC, Clang)
- OpenGL and GLUT libraries

Once you have the required software, you can compile and run the game by following these steps:

1. Clone the repository or download the source code files.
2. Compile the `main.cpp` file using your C++ compiler.
3. Link the OpenGL and GLUT libraries during the compilation process.
4. Run the compiled executable to start the game.

## Usage

The game can be played using the following controls:

- **Left Arrow Key**: Move the character to the left
- **Right Arrow Key**: Move the character to the right
- **Space Bar**: Jump

The objective of the game is to navigate through the levels, collect coins, and reach the end of the stage without colliding with obstacles or falling into the river.

## Classes and Functions

The game uses the following functions and classes:

- `Character` class: Represents the player character and handles its movement and collision detection.
- `Obstacle` class: Represents the obstacles in the game and checks for collisions with the character.
- `River` class: Represents the rivers in the game and checks for collisions with the character.
- `Coin` class: Represents the coins in the game and checks for collisions with the character.
- `cameraMovement()` function: Adjusts the camera position to center the stage around the character.
- `checkAllObstacleCollisions()` function: Checks for collisions between the character and all obstacles.
- `checkAllRiverCollisions()` function: Checks for collisions between the character and all rivers.
- `respawnCharacter()` function: Respawns the character after a collision.
- `drawScoreboard()` function: Displays the player's score.
- `drawLives()` function: Displays the player's remaining lives.

## Contributing

Contributions to the Super Mario game are welcome. If you find any issues or have suggestions for improvements, please feel free to submit a pull request or open an issue on the project's repository.
