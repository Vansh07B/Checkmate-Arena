# Chess Game - JavaScript Implementation

This is a chess game built with object-oriented JavaScript for human vs human play.

## Features

- Full chess board with proper piece movement
- Turn-based gameplay for two human players
- Legal move validation
- Check and checkmate detection
- Pawn promotion
- Castling support
- Piece capture with graveyard display
- Board flip functionality
- Drag and drop piece movement
- Click to move piece functionality

## How to Play

1. Open `chess.html` in your web browser
2. Click "Start Game" to begin
3. White moves first
4. Click on a piece to see its possible moves (highlighted squares)
5. Click on a highlighted square to move the piece
6. Game alternates between white and black turns
7. Game ends when one player is checkmated

## Files Structure

- `chess.html` - Main HTML file
- `chess.css` - Styling for the chess board and interface
- `Game.js` - Main game logic and rules
- `piece.js` - Piece movement calculations
- `Board.js` - Board display and user interaction
- `History.js` - Move history tracking
- `img/` - Chess piece images (not included)

## Technical Implementation

The game uses object-oriented JavaScript with the following main classes:

- `Game` - Manages game state, rules, and piece movements
- `History` - Tracks move history for potential undo functionality

The board uses a numerical position system where each square is numbered (11-88), making it easy to calculate piece movements and validate moves.

## Chess Piece Images

The chess piece images should be placed in an `img/` folder with the following naming convention:
- `white-pawn.webp`, `black-pawn.webp`
- `white-rook.webp`, `black-rook.webp`
- `white-knight.webp`, `black-knight.webp`
- `white-bishop.webp`, `black-bishop.webp`
- `white-queen.webp`, `black-queen.webp`
- `white-king.webp`, `black-king.webp`