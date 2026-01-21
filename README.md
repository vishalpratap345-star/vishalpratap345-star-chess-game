# vishalpratap345-star-chess-game

A simple, interactive chess game with a beautiful GUI that runs entirely in your web browser!

## Features

- ✨ Beautiful, modern user interface with gradient backgrounds
- ♟️ Full chess board with Unicode chess pieces
- 🎮 Click-to-move gameplay
- ✅ Valid move highlighting
- 🔄 Turn-based gameplay (White vs Black)
- 📊 Move history tracking
- ⚠️ Check and checkmate detection
- 🎯 Piece capture mechanics
- 🔄 New game button to restart

## How to Deploy Locally

### Option 1: Open Directly in Browser

1. Clone this repository:
   ```bash
   git clone https://github.com/vishalpratap345-star/vishalpratap345-star-chess-game.git
   cd vishalpratap345-star-chess-game
   ```

2. Open `chess.html` in your web browser:
   - **Windows**: Double-click the `chess.html` file
   - **Mac**: Right-click `chess.html` → Open With → Your preferred browser
   - **Linux**: `xdg-open chess.html` or double-click the file

### Option 2: Using Python HTTP Server

1. Navigate to the repository directory:
   ```bash
   cd vishalpratap345-star-chess-game
   ```

2. Start a local HTTP server:
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Python 2
   python -m SimpleHTTPServer 8000
   ```

3. Open your browser and navigate to:
   ```
   http://localhost:8000/chess.html
   ```

### Option 3: Using Node.js HTTP Server

1. Install http-server globally (if not already installed):
   ```bash
   npm install -g http-server
   ```

2. Navigate to the repository directory and start the server:
   ```bash
   cd vishalpratap345-star-chess-game
   http-server -p 8000
   ```

3. Open your browser and navigate to:
   ```
   http://localhost:8000/chess.html
   ```

## How to Play

1. **Starting the Game**: White always moves first
2. **Making a Move**: 
   - Click on a piece to select it (it will be highlighted in green)
   - Valid moves will be shown with light green squares
   - Click on a valid destination square to move the piece
3. **Capturing Pieces**: Click on an opponent's piece when it's highlighted as a valid move
4. **New Game**: Click the "New Game" button to restart the game
5. **Move History**: The last 10 moves are displayed below the board

## Chess Rules Implemented

- ♟️ **Pawn**: Moves forward one square (or two from starting position), captures diagonally
- ♜ **Rook**: Moves horizontally or vertically any number of squares
- ♞ **Knight**: Moves in an L-shape (2 squares in one direction, 1 square perpendicular)
- ♝ **Bishop**: Moves diagonally any number of squares
- ♛ **Queen**: Moves horizontally, vertically, or diagonally any number of squares
- ♚ **King**: Moves one square in any direction
- ⚠️ **Check**: Warns when the king is under attack
- 🏁 **Checkmate**: Game ends when the king cannot escape from check

## Technologies Used

- HTML5
- CSS3 (with modern gradients and animations)
- Vanilla JavaScript (no external dependencies)

## Browser Compatibility

Works on all modern browsers:
- ✅ Chrome/Edge (Chromium)
- ✅ Firefox
- ✅ Safari
- ✅ Opera

## Screenshots

The game features:
- A gradient purple background
- Professional chess board with alternating light and dark squares
- Large, clear Unicode chess pieces
- Smooth hover effects and piece selection
- Real-time turn indicator
- Clean, modern design

Enjoy your game of chess! ♔♚