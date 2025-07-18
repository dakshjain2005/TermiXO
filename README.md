
# ❌ TermiXO

**TermiXO** is a terminal-based Tic Tac Toe game written in modern C++. It supports two-player mode, clean grid visuals, and accurate win detection. Simple, minimal, and fun for beginners to code or play!

---

## 🎮 Game Features

- 3x3 grid rendered using `std::cout`
- Player turns with marker switching (X and O)
- Input validation (occupied cells and invalid slots)
- Win detection (rows, columns, diagonals)
- Tie detection
- Friendly terminal UI with clear prompts

---

## ▶️ How to Play

1. **Run the game**
   ```bash
   g++ tictactoe.cpp -o termixo
   ./termixo
   ```

2. **Choose marker**: Player 1 selects either X or O.

3. **Take turns**: Players take alternate turns placing markers by typing slot numbers (1–9).

4. **Win or Tie**: Game ends when someone wins or all cells are filled.


---

## 🧠 How It Works

- The board is a `3x3 char array`.
- The `winner()` function checks win conditions after every move.
- The game uses simple math to convert 1–9 slot into 2D indices.

---

## 🧱 Code Structure

- `drawBoard()` – prints current game board
- `placeMarker()` – validates and updates board
- `winner()` – checks win state
- `swapPlayerAndMarker()` – switches turns
- `game()` – main game loop logic

---

## 👨‍💻 Author

- **Daksh Jain** – [@dakshjain2005](https://github.com/dakshjain2005)

---

## 📝 License

This project is licensed under the MIT License – see [LICENSE](../LICENSE) for details.
