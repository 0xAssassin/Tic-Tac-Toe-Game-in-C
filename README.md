# Tic-Tac-Toe Game in C

A simple **command-line Tic-Tac-Toe game** written in C for two players.

This project is designed as a beginner-friendly C programming project to practice **arrays, functions, loops, conditionals, input handling, and game logic**.

## 🎮 How the Game Works

The game uses a 3×3 board with positions numbered from **1 to 9**:

```text
 1 | 2 | 3
---|---|---
 4 | 5 | 6
---|---|---
 7 | 8 | 9
```

* **Player 1** uses `O`
* **Player 2** uses `X`
* Players take turns entering a position from **1 to 9**
* A position cannot be selected if it is already occupied
* The game ends when a player gets three symbols in a row
* If all positions are filled without a winner, the game is declared a draw

## 🧠 Concepts Used

* `char` arrays
* Functions
* `if-else` conditions
* `while` loop
* `scanf()` and `getchar()`
* `system("cls")`
* Array indexing
* Input validation
* Win and draw detection

## 📂 Main Functions

### `gameManual()`

Displays the position guide for the Tic-Tac-Toe board.

### `printBoard(char arr[])`

Displays the current game board.

### `playerChance(char arr[], int player)`

Checks whether the entered position is valid and available.

### `printOutput(char arr[])`

Clears the console and displays the updated game state.

### `win(char arr[])`

Checks all possible winning combinations and also detects a draw.

## ▶️ How to Run

Compile the program using a C compiler:

```bash
gcc tic_tac_toe.c -o tic_tac_toe
```

Then run:

```bash
tic_tac_toe
```

On Windows:

```bash
tic_tac_toe.exe
```

## 📌 Example

```text
Player 1 turn: 5
Player 2 turn: 1
Player 1 turn: 9
Player 2 turn: 2
...
```

The board is updated after every valid move.

## 🛠️ Future Improvements

Possible improvements for this project include:

* Single-player mode against the computer
* Score tracking
* Replay option
* Better input validation
* Cross-platform screen clearing
* Colored game interface
# Tic-Tac-Toe-Game-in-C
A simple command-line Tic-Tac-Toe game written in C. It supports two players, position validation, turn handling, win detection, and draw detection using arrays, functions, loops, and conditional statements.
