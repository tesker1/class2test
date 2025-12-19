# Class2Test Project

A web application featuring user authentication and classic games.

## Features

### User Authentication
- Create accounts with email and password
- Login to access private sections
- Profile page for authenticated users
- Built with Supabase Authentication

### Tic Tac Toe Game
- Classic 3x3 grid gameplay
- Both single-player (vs computer AI) and two-player modes
- Strategic computer AI that blocks wins and makes smart moves
- Toggle between game modes with dedicated buttons
- Win detection for all possible winning combinations
- Draw detection when board is full
- Score tracking for wins and draws
- Clean, modern UI with responsive design
- Easy "New Game" reset functionality

## How to Play Tic Tac Toe

1. Open `tic-tac-toe.html` in your web browser
2. Choose your game mode:
   - **vs Computer**: Play against an AI opponent (default)
   - **2 Players**: Play with another human player locally
3. If playing vs computer: You are X and go first. Click any empty cell to place your X marker
4. If playing 2-player: Player X goes first, then players alternate placing X or O markers
5. The computer AI will strategically block your winning moves and try to win
6. First player to get 3 in a row (horizontal, vertical, or diagonal) wins
7. If all 9 cells are filled without a winner, it's a draw
8. Click "New Game" to reset the board and play again
9. Scores are tracked at the bottom of the screen

## Files Structure

- `tic-tac-toe.html` - Complete tic-tac-toe game (HTML, CSS, JS)
- `docs/project-description.md` - Project overview and features
- `docs/features/` - Feature documentation
- `features/` - Feature specifications
- `LICENSE` - Project license

## Technology Stack

- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **Authentication**: Supabase (for user authentication feature)
- **Styling**: Modern CSS with gradients, animations, and responsive design

## Getting Started

1. Clone the repository
2. Open `tic-tac-toe.html` in any modern web browser to play the game
3. For the authentication feature, you'll need to set up Supabase (see user authentication docs)

The tic-tac-toe game is completely self-contained and requires no additional setup or dependencies.