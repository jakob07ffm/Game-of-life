# Game of Life - Pygame Implementation

## Overview

This project is a simple implementation of Conway's Game of Life using Pygame. The Game of Life is a cellular automaton devised by mathematician John Conway. It consists of a grid of cells that evolve over time based on a set of rules. Each cell can either be alive or dead, and its state in the next generation depends on the states of its eight neighbors.

## Rules of the Game

1. **Underpopulation**: A live cell with fewer than two live neighbors dies.
2. **Survival**: A live cell with two or three live neighbors remains alive.
3. **Overpopulation**: A live cell with more than three live neighbors dies.
4. **Reproduction**: A dead cell with exactly three live neighbors becomes alive.

## Project Structure

- **main()**: The entry point of the game where the game loop runs.
- **gen(num)**: Generates a set of random live cell positions.
- **draw_grid(positions)**: Draws the current state of the grid on the screen.
- **adjust_grid(positions)**: Adjusts the grid according to the rules of the Game of Life.
- **get_neighbors(pos)**: Returns the neighboring cells of a given position.

## Controls

- **Mouse Click**: Toggle the state of a cell between alive and dead.
- **Spacebar**: Start or pause the game.
- **C Key**: Clear the grid and pause the game.
- **G Key**: Generate a random set of live cells.

*This game was made with this tutorial: https://youtu.be/YDKuknw9WGs?si=rEJOxVY-_CPvuBJA*
