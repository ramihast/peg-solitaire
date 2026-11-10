# Peg Solitaire

A classic single-player puzzle game about planning jumps and removing pegs. Play in your browser on desktop, tablet, or mobile.

**Play online:** [ramihast.github.io/peg-solitaire](https://ramihast.github.io/peg-solitaire/)

## The Goal

Remove pegs from the board by jumping one peg over another. Try to finish with as few pegs as possible. Leaving exactly one peg on the board is a perfect win.

## The Board

The game uses the traditional English Peg Solitaire board:

- The board has 33 playable holes arranged in a cross.
- At the start, 32 holes contain pegs.
- The center hole is empty.

## How to Play

1. Select a peg by clicking or tapping it.
2. The game highlights the empty holes that peg can legally move to.
3. Select one of the highlighted holes to make the move.
4. The selected peg jumps horizontally or vertically over an adjacent peg and lands in the empty hole beyond it.
5. The peg jumped over is removed from the board.

Each move removes one peg. Continue until you have one peg left or no legal moves remain.

## Move Rules

A move is legal only when:

- The moving peg jumps in a straight horizontal or vertical line.
- There is another peg in the immediately adjacent hole.
- The hole immediately beyond that peg is empty.
- All three holes are playable positions on the board.

Diagonal jumps, jumps over empty holes, and moves into occupied or unavailable holes are not allowed.

## Controls

- **Select a peg:** Click or tap a peg.
- **Move a peg:** Click or tap one of its highlighted destinations.
- **Cancel selection:** Select the same peg again, tap an empty area, or press `Escape`.
- **Undo:** Reverses the last move. You can undo repeatedly.
- **Redo:** Restores a move that was undone.
- **Hint:** Highlights a legal move without making it for you.
- **New Game / Restart:** Starts the game over. Confirm if a game is in progress.

The game also supports keyboard play:

- Use the **arrow keys** to move focus between holes.
- Press **Enter** or **Space** to select a peg or activate a highlighted destination.
- Press **Escape** to cancel a selection.

## Game Status

The game displays the number of pegs remaining and the number of moves made. When no legal moves remain, the game ends and reports the result.

- **1 peg remaining:** You solved the puzzle perfectly.
- **More than 1 peg remaining:** The game shows how many pegs remain.

Use **Undo** to try a different sequence or **New Game** to start again.

## Tips

- Look for moves that open up new empty holes.
- Avoid leaving isolated pegs that cannot reach the rest of the board.
- Plan several jumps ahead when possible.
- Use **Hint** to explore a move, then use **Undo** if you want to try another path.

## Run Locally

1. Download or clone this repository.
2. Open `index.html` in a modern web browser.

The game is a self-contained static page and does not require installation or a server.

## Project

This project is made with:

- HTML
- CSS
- JavaScript

## License

No license has been specified for this project.
