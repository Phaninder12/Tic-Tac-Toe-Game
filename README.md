# Tic-Tac-Toe-Game

Overview
Tic Tac Toe is a classic two-player game where players take turns marking spaces in a 3x3 grid with their symbol (X or O). The first player to align three of their symbols horizontally, vertically, or diagonally wins. If all spaces are filled without a winner, it's a draw.
This project implements a simple Tic Tac Toe game using HTML, CSS, and JavaScript. It's designed to run in the browser and can be easily extended for AI opponents or multiplayer features.
Features

Two-Player Mode: Alternate turns between X and O players.
Win Detection: Automatically checks for wins after each move.
Draw Detection: Identifies full board ties.
Reset Game: Button to start a new game.
Responsive Design: Works on desktop and mobile devices.

Technologies Used

HTML5: For the game structure and board layout.
CSS3: For styling the grid and animations (e.g., highlighting wins).
JavaScript (ES6): Handles game logic, event listeners, and state management.


Installation

Clone or download the repository:
textgit clone https://github.com/Phaninder12/tic-tac-toe.git

Open index.html in a web browser.
Alternatively, deploy to GitHub Pages (see Deployment section).

No additional setup or dependencies required!
Usage

Open index.html in your browser.
Player X starts by clicking any empty cell in the 3x3 grid.
Players alternate turns by clicking empty cells.
The game announces the winner or draw.
Click "Restart Game" to reset.

Example Gameplay

Board starts empty.
After moves: X in top-left, O in center, etc.
Win example: Three X's in a row triggers "X Wins!" alert and highlights the line.

Game Logic
The JavaScript maintains a board array (9 elements for the grid) and a currentPlayer variable. Key functions:

makeMove(index): Updates board and switches players.
checkWin(): Scans for three-in-a-row using predefined win combinations.
isBoardFull(): Checks for draws.

Screenshots
<img width="1920" height="1200" alt="Screenshot (214)" src="https://github.com/user-attachments/assets/cd056051-478e-40c5-9730-9d8d68abd2ea" />


Fork the repo.
Create a feature branch (git checkout -b feature/AmazingFeature).
Commit changes (git commit -m 'Add some AmazingFeature').
Push to branch (git push origin feature/AmazingFeature).
Open a Pull Request.

Deployment to GitHub Pages

Create a new repository on GitHub (e.g., tic-tac-toe).
Push your code to the main branch.
Go to Settings > Pages.
Set Source: Deploy from a branch > main > / (root).
Your site will be live at https://Phaninder12.github.io/tic-tac-toe/.

License
This project is licensed under the MIT License - see the LICENSE file for details.
