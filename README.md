# chess.mini

A fully functional, console-based chess engine written in Python. Built from scratch as a proof of concept and foundation for "Chessvania"-- a larger, more ambitious project.

## Overview

chess.mini implements a complete two-player chess game playable in the terminal. The goal was to develop and validate the core game logic of a chess engine, its rules, and its architecture in a clean and contained environment before scaling up.

## Features

- Full chess rule implementation including:
  - En passant
  - Castling (kingside and queenside)
  - Pawn promotion
  - Check and checkmate detection
  - Stalemate detection
  - Threefold repetition draw
  - 50-move rule draw
- Unicode piece rendering in the terminal
- Turn-based input with move validation
- Board state tracking

## How to Run

Requires Python 3.x. No dependencies.

```bash
python chess.mini.py
```

Moves are entered in algebraic notation:

```
Enter your move (e.g., 'e2 e4')
```

## Limitations

- Global mutable state (intentional for this prototype)
- Text-only interface
- No AI opponent
- No saved games or move history export

## Author

Hassan Khan — 2025
