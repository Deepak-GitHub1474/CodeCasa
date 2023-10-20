# Tic Tac Toe Game Using React

### The project is deployed on Netlify, and the repository is available on GitHub.

- Netlify Link 👉
[https://developerstringtictactoe.netlify.app/]

- GitHub Repo Link 👉
[https://github.com/Deepak-GitHub1474/CodeCasa/tree/main/Tic_Tac%20_Toe]

### Project Features:

1. Game Board
    - The game board is a 3x3 grid where players can make their moves.

2. Player Turns
    - Players take turns, with "X" and "O" alternating as their markers.
    - The game starts with "X."

3. Winning Condition
    - The game checks for a winner after each move.
    - If a player has three of their markers in a row horizontally, vertically, or diagonally, they win.

4. Draw Condition
    - If all the squares are filled, and no player has won, the game ends in a draw.

5. Restart Button
    - A "Restart Game" button is available.
    - It's initially disabled and can only be used after the game has finished (a win or draw).

6. Next Player Display
    - The status at the top of the game board shows the next player.
    - For example, "Next player: X" means it's "X's" turn to play.

### How the Code Works:
    - The game state is stored in the board array, which represents the 3x3 grid.
    - The xIsNext variable keeps track of the current player.
    - The restartButtonDisabled variable controls the restart button's availability.
    - The calculateWinner function checks for a winner.
    - The handleClick function allows players to make their moves.
    - After each move, it checks for a win or a draw, enabling the restart button if needed.
    - The restartGame function resets the game when the restart button is pressed.
    - The renderSquare function renders each square on the game board.
    - The getStatus function displays the current game status.

### Conclusion:
The Tic Tac Toe game project in React is now complete, allowing players to enjoy a simple yet classic game.
It includes features like player turns, win conditions, draw conditions, and a restart button. The code is 
functional and straightforward, providing an enjoyable gaming experience.

### If you have any further suggestions or questions, please let me know.

### My Linkedin Profile Link 👉
[https://www.linkedin.com/in/deepak-chaudhary1474/]