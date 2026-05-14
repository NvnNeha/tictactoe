# Tic Tac Toe

A simple, browser-based Tic Tac Toe game for two players with a live scoreboard.

## Features

- Two-player local gameplay (Player X vs Player O)
- Live scoreboard tracking wins for both players and draws
- Winning row/column/diagonal is highlighted with a pulsing glow
- Restart the current round without losing scores
- Reset all scores back to zero
- Responsive layout that works on smaller screens

## How to Play

1. Open `index.html` in any modern web browser.
2. Player X always starts. Click any empty cell to place your mark.
3. Players alternate turns. Get three of your marks in a row — horizontally, vertically, or diagonally — to win.
4. The scoreboard at the top updates automatically:
   - **Player X** — wins by X
   - **Draws** — games that ended without a winner
   - **Player O** — wins by O
5. Click **Restart Round** to clear the board and start a new round (scores are kept).
6. Click **Reset Scores** to set all scores back to zero and start fresh.

## Files

- `index.html` — markup for the board, scoreboard, and controls
- `style.css` — styling, layout, and animations
- `script.js` — game logic, win detection, and score tracking

## Running Locally

No build step or dependencies — just open the file:

```bash
open index.html
```

Or serve the directory with any static file server if you prefer.
