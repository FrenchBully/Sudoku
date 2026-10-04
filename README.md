# Large-Button Sudoku

A free, easy-to-use Sudoku game designed for older adults and anyone who finds small buttons hard to tap. It runs in any web browser, with nothing to install and no account to create.

**Play it:** https://yourusername.github.io/sudoku/

## Features

- **Big, simple controls.** The number keys, Undo, Erase, and Hint buttons are all extra large, and nothing requires dragging, holding, or double-tapping.
- **Three levels.** Easy, Medium, and Hard, each described in plain language.
- **Step-by-step guidance.** A message above the number pad always says what to do next.
- **Clear mistakes.** Wrong numbers turn red and get a ✕ mark, so the warning doesn't depend on color alone.
- **Easy on the eyes.** High-contrast colors, a typeface designed for low vision ([Atkinson Hyperlegible](https://brailleinstitute.org/freefont)), and automatic dark mode.
- **Never runs out of puzzles.** Every puzzle is freshly generated and has exactly one solution.
- **Picks up where you left off.** Progress is saved automatically in your browser.
- **No tracking.** There are no ads, accounts, or analytics, and nothing leaves your device.

## How to play

Fill every row, column, and 3×3 box with the numbers 1 to 9, with no repeats.

1. Tap an empty square.
2. Tap a number.
3. Use **Undo** to take back a move, **Erase** to clear a square, or **Hint** to fill in a correct number.

## Add it to an iPad or iPhone

1. Open the game's address in **Safari**.
2. Tap the **Share** button, then **Add to Home Screen**.
3. Always open the game from that icon so your saved puzzle stays in one place.

On Android, open the game in Chrome, then use the menu and choose **Add to Home screen**.

## Run it yourself

The whole game is a single static file, so there is no build step.

- **Locally:** download `index.html` and open it in a browser.
- **GitHub Pages:** upload `index.html` and `apple-touch-icon.png` to a public repository, then go to **Settings → Pages** and choose the `main` branch and `/ (root)`.

## How difficulty works

Difficulty is set by how many numbers are given at the start: 44 for Easy, 34 for Medium, and 28 for Hard. Puzzles are not rated by the solving techniques they require.

## Project files

| File | Purpose |
| --- | --- |
| `index.html` | The complete game (HTML, CSS, and JavaScript) |
| `apple-touch-icon.png` | Icon used when added to an iPad or iPhone home screen |

## Contributing

Suggestions are welcome, especially ideas that make the game easier to use. Please open an issue to describe what would help.

## License

No license has been chosen yet. Until one is added, all rights are reserved by the author.
