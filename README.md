# Memory Matching Game

This is a simple memory matching game built with JavaScript. The goal is to match pairs of colored tiles by clicking on them.

How to Play
Click on a tile to reveal its color.
Click on a second tile to try to find its matching pair.
If the colors match, the tiles will remain revealed.
If the colors don't match, they will briefly flash and then be hidden again.
Continue matching pairs until all tiles are revealed.
You win when all tiles are matched!
Features
Randomly generated tile arrangements for each playthrough.
Visual feedback for matching and non-matching tiles.
Win condition when all tiles are matched.
Technologies Used
JavaScript
HTML (for the game board structure)
CSS (for visual styling)
Getting Started
Open the index.html file in your web browser.
Start playing!
Additional Information
The game uses a colorsPickList array to store the available colors.
The buildTile function creates individual tile elements with click event listeners.
The game state is managed using variables like revealedCount, activeTile, and awaitingEndOfMove.
Contributing
Feel free to fork this repository and create pull requests to contribute to the project.

Happy matching!
