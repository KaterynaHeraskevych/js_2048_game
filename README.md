
A browser implementation of the classic 2048 puzzle game built with vanilla JavaScript.

This project was developed from a technical specification with predefined requirements, game rules, and API methods. The main focus was implementing game mechanics, state management, and movement algorithms from scratch.

## Live Demo

[Play the Game](https://KaterynaHeraskevych.github.io/js_2048_game/)

## Features

- 4x4 interactive game board
- Full movement support:
  - Left
  - Right
  - Up
  - Down
- Tile merge logic following original 2048 rules
- Random tile generation after valid moves
- Score calculation system
- Win condition detection (2048 tile)
- Game over detection
- Restart functionality
- Keyboard controls
- Dynamic DOM rendering

## Technologies Used

- JavaScript (ES6+)
- HTML5
- CSS3

## Technical Challenges

While building this project, I implemented:

- Complex movement algorithms for all directions
- Tile merge mechanics without double merges
- 2D array manipulation for board state management
- Game state synchronization with the UI
- Randomized tile generation with probability rules
- Win and lose condition detection
- Keyboard event handling
- Object-oriented architecture using a dedicated `Game` class

## Game Architecture

The project is divided into two main parts:

### Game Logic

Implemented in:

```text
src/modules/Game.class.js
