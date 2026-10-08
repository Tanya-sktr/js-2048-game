# JS2048

## Introduction

Welcome to the **JS2048** project, a JavaScript implementation of the classic 2048 puzzle game.

The game is played on a 4×4 grid where players move numbered tiles using the arrow keys. Tiles with the same value merge when they collide, and the goal is to reach the 2048 tile.

The project was created to practice JavaScript game logic, state management, DOM rendering, responsive layout, and user interaction.

### Key Features

- **Tile Movement:** Move tiles using the keyboard arrow keys.
- **Tile Merging:** Tiles with the same value merge into one tile with double the value.
- **Random Tile Generation:** New tiles appear after valid moves.
- **Score Tracking:** The score updates when tiles are merged.
- **Win Condition:** The game is won when the 2048 tile is created.
- **Lose Condition:** The game ends when there are no empty cells and no possible merges.
- **Restart Functionality:** The game can be restarted at any time.
- **Responsive Design:** The layout adapts to different screen sizes.
- **Smooth UI Transitions:** Includes transitions and visual feedback for interactions.

## Challenges

Developing JS2048 involved several challenges related to game logic and state management.

### Key Challenges

1. **Tile Movement and Merging:** Implementing correct movement in all four directions and ensuring that tiles merge only once per move.
2. **Game State Management:** Keeping the board state, score, and game status synchronized.
3. **Win and Lose Logic:** Correctly detecting when the player wins or when no valid moves remain.
4. **Random Tile Generation:** Adding new tiles only after valid moves and placing them in empty cells.
5. **DOM Rendering:** Updating the game board and score based on the current game state.

## Technical Requirements

To run this project, you will need:

- **Modern web browser:** Latest version of Chrome, Firefox, Safari, or Edge.
- **Node.js:** Required to run the development environment.
- **NPM:** Used to install dependencies and run project scripts.

## Installation and Setup

To install the project and run it locally, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Tanya-sktr/js-2048-game.git
   ```

2. **Navigate to the project directory:**

   ```bash
   cd js-2048-game
   ```

3. **Install dependencies:**

   ```bash
   npm install
   ```

4. **Start the local development server:**

   ```bash
   npm start
   ```

## Usage

After starting the project, it will be available at:

`http://localhost:1234`

Click the **Start** button to begin the game.

Use the keyboard arrow keys to move the tiles:

- `ArrowUp` — move tiles up
- `ArrowDown` — move tiles down
- `ArrowLeft` — move tiles left
- `ArrowRight` — move tiles right

Merge tiles with the same value and try to reach **2048**.

## Example

You can play the deployed version here:

[DEMO LINK](https://tanya-sktr.github.io/js-2048-game/)

## Technologies Used

This project was built using the following technologies:

- **HTML5:** For the game structure and layout.
- **SCSS:** For styling, responsive design, and reusable styles.
- **JavaScript (ES6):** For game logic, state management, and interactivity.
- **Parcel:** For local development and production builds.
- **Node.js:** For running the development environment.
- **NPM:** For dependency management and scripts.
- **Git:** For version control.
- **GitHub:** For hosting the repository.
- **GitHub Pages:** For deploying the live demo.

## Design Specifications

- **Desktop:** 1280px
- **Tablet:** 640px
- **Mobile:** 320px and above

## Contribution Guidelines

If you wish to contribute to this project, please follow these guidelines:

1. **Fork the repository:** Create your own copy of the project on GitHub.
2. **Clone your fork:** Download your copy to your local machine.
3. **Create a branch:** Develop your feature or fix on a separate branch.
4. **Submit a pull request:** Propose your changes to be merged into the main project.

## License

This project is licensed under the GPL-3.0 License - see the [LICENSE](https://github.com/Tanya-sktr/js-2048-game/blob/master/LICENSE) file for details.
