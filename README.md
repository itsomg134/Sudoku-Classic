#  Sudoku Classic

A beautifully crafted, fully playable Sudoku game built with vanilla HTML5, CSS, and JavaScript. No dependencies, no backend — just pure logic and clean design.

![Sudoku Game Preview](https://via.placeholder.com/800x450?text=Sudoku+Game+Preview)

##  Features

- **Interactive 9x9 Grid** – Click any cell and use your keyboard to play
- **Three Difficulty Levels** – Easy (48 clues), Medium (38 clues), Hard (28 clues)
- **Move Counter** – Track your progress with every number placement
- **Visual Feedback** – Color-coded numbers:
  -  Green for fixed clue cells
  -  Blue for correct user entries
  -  Red for incorrect entries
- **Keyboard Controls** – Full keyboard support for power users
- **Responsive Design** – Plays beautifully on desktop, tablet, and mobile devices
- **New Game & Reset** – Generate fresh puzzles or restart the current one

##  How to Play

1. **Select a cell** – Click or tap on any empty cell (or a non-fixed cell you want to change)
2. **Enter a number** – Press keys `1` through `9` on your keyboard
3. **Remove a number** – Press `Delete`, `Backspace`, or `0`
4. **Navigate** – Use arrow keys to move between cells quickly
5. **Win the game** – Fill every row, column, and 3×3 box with numbers 1–9 without repetition

##  Controls Summary

| Action | Keyboard |
|--------|----------|
| Select cell | Click / Tap |
| Enter 1–9 | Number keys `1`–`9` |
| Clear cell | `Delete` / `Backspace` / `0` |
| Move selection | Arrow keys (↑ ↓ ← →) |
| New puzzle | Click "New Game" button |
| Reset puzzle | Click "Reset" button |
| Change difficulty | Click Easy / Medium / Hard |

##  Game Logic

- Every puzzle is **guaranteed to have a unique solution**
- Puzzles are generated dynamically using backtracking algorithms
- Fixed clue cells cannot be edited – they form the puzzle's foundation
- Your moves are counted only when you actually change a value
- Victory is detected automatically – celebration message appears when solved

##  Getting Started

### Play Online (GitHub Pages)

1. Clone or download this repository
2. Open `index.html` in any modern web browser
3. Start playing instantly – no installation required!

### Local Development

```bash
# Clone the repository
git clone https://github.com/yourusername/sudoku-classic.git

# Navigate to the folder
cd sudoku-classic

# Open in your browser
open index.html   # macOS
start index.html  # Windows
xdg-open index.html # Linux
```

##  Visual Design

- **Warm, paper-like theme** – Soft beige and cream colors mimic traditional puzzle books
- **Bold subgrid borders** – Clear visual separation of 3×3 blocks
- **Subtle hover effects** – Smooth interactions with visual feedback
- **Glass-morphism container** – Modern backdrop blur effect on the game wrapper
- **Responsive scaling** – Canvas scales gracefully on any screen size

##  Technical Details

- **Pure vanilla implementation** – No external libraries or frameworks
- **Canvas rendering** – Smooth, fast, pixel-perfect drawing
- **Backtracking solver** – Generates valid puzzles and ensures unique solutions
- **Event-driven architecture** – Responsive keyboard and mouse/touch handling
- **Mobile-ready** – Touch events work seamlessly on smartphones and tablets

##  Project Structure

```
sudoku-classic/
├── index.html          # Complete game (HTML, CSS, JS all in one)
├── README.md           # This file
└── screenshot.png      # (Optional) Game screenshot
```

##  Customization

Want to tweak the game? Here are some easy modifications:

- **Change difficulty presets** – Modify `cluesToKeep` values in `removeCellsFromSolution()`
- **Adjust colors** – Edit the CSS variables and canvas drawing logic
- **Add pencil marks** – Extend the grid to support candidate notes
- **Change board size** – Modify `SIZE` and `SUBGRID` constants (advanced)

##  Browser Support

| Browser | Version |
|---------|---------|
| Chrome | 90+ |
| Firefox | 88+ |
| Safari | 14+ |
| Edge | 90+ |
| Mobile browsers | iOS Safari, Chrome Android |

##  Contributing

Contributions are welcome! Here are some ideas:

- Add a timer to track solve time
- Implement "Hint" system
- Save game state to localStorage
- Add undo/redo functionality
- Create a dark mode theme
- Export/import puzzle strings

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

##  License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.

##  Acknowledgments

- Classic Sudoku puzzle rules and logic
- Backtracking algorithm inspiration from computer science fundamentals
- Icons and emojis for visual flair

##  Contact

Om Gedam

GitHub: [https://github.com/itsomg134](https://github.com/itsomg134)

Email: [omgedam123098@gmail.com](mailto:omgedam123098@gmail.com)

Twitter (X): [https://twitter.com/omgedam](https://twitter.com/omgedam)

LinkedIn: [https://linkedin.com/in/omgedam](https://linkedin.com/in/omgedam)

Portfolio: [https://ogworks.lovable.app](https://ogworks.lovable.app)

