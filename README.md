# Tic-Tac-Toe
# Tic Tac Toe Game

## Overview
This is a simple implementation of the classic Tic Tac Toe game built using HTML, CSS, and JavaScript. The game allows two players to take turns marking spaces on a 3x3 grid, aiming to align three of their marks either horizontally, vertically, or diagonally to win.

## Features
- Interactive 3x3 game grid.
- Supports two-player mode.
- Dynamic game status updates (e.g., "Player X's turn", "Player O wins").
- Restart button to reset the game board and start a new match.

## Technologies Used
- **HTML**: For the structure of the game board and layout.
- **CSS**: For styling the game board and enhancing the user interface.
- **JavaScript**: For game logic, handling user interactions, and determining the game outcome.

## How to Play
1. Open the `index.html` file in your web browser.
2. The game board will be displayed with a 3x3 grid.
3. Player X starts first by clicking on a cell in the grid to place their mark.
4. Player O takes the next turn.
5. Players alternate turns until one player aligns three marks (X or O) horizontally, vertically, or diagonally, or the grid is fully occupied (resulting in a draw).
6. Click the "Restart" button to play again.

## Project Structure
```
TicTacToe/
├── index.html   # Main HTML file
├── style.css    # Stylesheet for the game
└── script.js    # JavaScript file containing game logic
```

## Code Highlights
- **HTML**:
  - Defines the grid using a `div` container with 9 cells.
  - Includes a section to display game status and a restart button.

- **CSS**:
  - Styles the grid to ensure uniform cell sizes and borders.
  - Highlights the winning combination for better user feedback.

- **JavaScript**:
  - Manages player turns and validates game states.
  - Checks for win conditions and displays the winner or draw.
  - Provides functionality to reset the game state.

## Example Screenshot
*Add a screenshot of your game interface here.*

## Future Enhancements
- Add an AI opponent for single-player mode.
- Implement a scoreboard to track wins and losses.
- Allow players to customize their names and marks.

## Contributing
If you'd like to contribute to this project, feel free to fork the repository and submit a pull request.

## License
This project is licensed under the MIT License.

