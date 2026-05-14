# EgoChess

A reverse-chess game where you and the AI compete to **lose** instead of win.

## Overview

EgoChess is a unique chess variant where the traditional objective is inverted. The bot uses sophisticated AI to *force* you into a winning position while actively trying to get itself checkmated. Your goal is to maintain enough control to avoid accidentally winning.

## Features

- **Anti-Chess AI**: Minimax algorithm with Alpha-Beta pruning optimized to lose
- **Board Flipping**: Play as White or Black. The board rotates each New Game
- **Offline-First**: No server required—everything runs in your browser

## How to Play

1. Open `https://kale-wu.github.io/EgoChess/` in any modern browser
2. Click or drag pieces to move them
3. The bot will automatically respond with its "losing" strategy
4. **Stack premoves** by making moves while it's the bot's turn
5. **Right-click** to clear all queued premoves
6. **New Game** switches your color and starts fresh

## Strategy Tips

- The bot will sacrifice pieces aggressively—don't panic
- Try to avoid taking the bot's pieces when possible
- Set up scenarios where the bot *must* give away material
- Patience and precise play can force the bot's defeat

## Technical Details

- Built with vanilla JavaScript and [Chess.js](https://github.com/jhlywa/chess.js)
- Depth-3 Minimax tree search

## License

MIT

Enjoy the mind-bending game of ego-chess!
