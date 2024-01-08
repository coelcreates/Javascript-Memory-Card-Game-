# Memory Matching Game

**A simple memory matching game built with JavaScript.**

## How to Play

1. Click on a tile to reveal its color.
2. Click on a second tile to try to find its matching pair.
3. If the colors match, the tiles will remain revealed.
4. If the colors don't match, they will briefly flash and then be hidden again.
5. Continue matching pairs until all tiles are revealed.
6. You win when all tiles are matched!

## Features

- Randomly generated tile arrangements for each playthrough.
- Visual feedback for matching and non-matching tiles.
- Win condition when all tiles are matched.

## Technologies Used

- JavaScript
- HTML
- CSS

## Getting Started

1. Open the `index.html` file in your web browser.
2. Start playing!

## Additional Information

- The game uses a `colorsPickList` array to store the available colors.
- The `buildTile` function creates individual tile elements with click event listeners.
- The game state is managed using variables like `revealedCount`, `activeTile`, and `awaitingEndOfMove`.

## Contributing

Feel free to fork this repository and create pull requests to contribute to the project.

**Happy matching!**
