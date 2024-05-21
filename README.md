# Infinite Tic Tac Toe Game

## Overview

Infinite Tic Tac Toe is a dynamic twist on the classic Tic Tac Toe game where players can expand the board and use special "block" moves. This README will guide you through the rules, setup, and gameplay mechanics.

## Table of Contents

1. [Game Rules](#game-rules)
2. [Setup](#setup)
3. [Gameplay](#gameplay)
   - [Basic Moves](#basic-moves)
   - [Block Moves](#block-moves)
   - [Winning the Game](#winning-the-game)
4. [Technical Details](#technical-details)
5. [Contributing](#contributing)
6. [License](#license)

## Game Rules

### Basic Rules

- The game is played by two players who take turns.
- Players can place their symbol (X or O) on any empty cell of the board.
- The board is initially 3x3 but can be expanded by the players.
- To win, a player must align a specified number of their symbols (e.g., 3 in a row for classic, or a larger number for bigger boards).

### Board Expansion

- Players can expand the board by one row or column in any direction on their turn, except when using a block move.
- The expansion does not count as a turn. Players still need to place their symbol after expanding the board.

### Block Moves

- A block move allows a player to block an opponent's potential winning move.
- Using a block move grants the player an additional turn.
- Block moves cannot be used to directly create a winning line for the blocking player.
- If a block move results in a potential win for the blocking player, the move is invalid and must be redone.

### Restrictions on Block Moves

- Block moves are limited to preventing the opponent's immediate win and should not be used excessively to prolong the game unfairly.

## Setup

### Prerequisites

- Python 3.x installed on your system.
- Optional: A virtual environment for Python dependencies.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/infinite-tic-tac-toe.git
   cd infinite-tic-tac-toe
