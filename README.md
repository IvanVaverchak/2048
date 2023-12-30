2048 Game Implementation

This project implements the classic 2048 game using HTML, CSS (compiled from SCSS), and JavaScript. The game features a 4x4 grid where players can slide numbered tiles to combine them, aiming to reach the elusive 2048 tile and achieve victory. The code is organized into sections to handle game mechanics, user interactions, and UI updates.

JavaScript (main.js)

Initialization and Variables: The game starts by defining essential variables, including the game field, score, and various HTML elements. Event listeners are set up for the "Start" button and keyboard arrow keys.

Game Logic:

The setNewCell function generates a new tile (either 2 or 4) in a random empty cell.
The move functions handle tile movement in different directions (left, right, up, down) by merging adjacent identical tiles.
checkIfPossible verifies if there are possible moves left on the board.
checkIfWin checks for a win condition when a tile with the value 2048 is reached.
checkIfLose checks for a lose condition and displays the appropriate message.

Update Functions:

updateCell updates the visual representation of a single cell based on its value.
updateGame refreshes the entire game grid and score display.
Event Listeners:

The "Start" button initializes a new game, resets the score, and hides any messages.
Keyboard arrow keys trigger corresponding moves when the game is active.
HTML (index.html)

Structure:

The HTML file defines the basic structure of the game, including the score display, "Start" button, and message container.

SCSS: Stylesheets are written in SCSS is employed for a more maintainable and organized styling structure.

Message Container:

Messages for game start, win, and lose conditions are displayed within a designated container.

Game Field:

The table structure represents the game field with empty cells initially.

How to Play:
Press "Start" to begin the game.
Use arrow keys to slide tiles in different directions.
Combine identical tiles to reach 2048 and win the game.
Enjoy playing the 2048 game! Feel free to restart anytime.

[DEMO LINK](https://IvanVaverchak.github.io/2048/)
