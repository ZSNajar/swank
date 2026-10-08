# Swank

A daily minefield puzzle. Drive a tank across a new board every day to find the hidden key. Everyone gets the same board, and it gets harder from Monday to Sunday.

Play it at https://zsnajar.github.io/swank/

- Tiles you drive on show how many mines touch them (up, down, left, right).
- The key distance tells you how many steps away the key is.
- Shots destroy a mine, or prove a tile is safe.
- Par is how many moves a logic-only solver needed.

The whole game is one file, `index.html`. Boards are generated in the browser from the date, so there is no server.
