# 2048 Game

## Overview

This project is a browser-based implementation of the classic 2048 game.

The goal of the game is to move and merge tiles with the same value until
you create a tile with the number 2048.

The project was built with JavaScript, HTML, and SCSS and includes game
logic, score tracking, win and lose states, keyboard controls, and restart
functionality.

## Live Preview

[Play the game](https://tanya-sktr.github.io/js-2048-game/)

## Features

- Classic 4×4 game board
- Keyboard controls using arrow keys
- Random generation of new tiles
- Tile merging logic
- Score tracking
- Win state when the 2048 tile is reached
- Lose state when no valid moves remain
- Start and restart functionality
- Responsive layout
- Smooth UI transitions

## How to Play

- Click the **Start** button to begin the game.
- Use the arrow keys:
  - ↑ Move tiles up
  - ↓ Move tiles down
  - ← Move tiles left
  - → Move tiles right
- Tiles with the same value merge when they collide.
- Each merge increases your score.
- Reach the **2048** tile to win.
- The game ends when there are no empty cells and no possible merges.
- Click **Restart** to start a new game.

## Controls

- `ArrowUp` — move tiles up
- `ArrowDown` — move tiles down
- `ArrowLeft` — move tiles left
- `ArrowRight` — move tiles right

## Technologies Used

- HTML5
- SCSS
- JavaScript
- Parcel
- Git
- GitHub Pages

## Getting Started

```bash
git clone https://github.com/Tanya-sktr/js-2048-game.git
cd js-2048-game
npm install
npm start
