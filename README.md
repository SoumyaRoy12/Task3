            /*OVERVIEW OF TIC-TAC-TOE GAME*/

Creating a Tic-Tac-Toe game in C++ involves designing the game board, handling player turns, checking for a win or a draw, and allowing players to make moves. 

### Explanation:
- **Board Representation:** Uses a 2D vector (`std::vector<std::vector<char>>`) to represent the 3x3 Tic-Tac-Toe board.
- **Game Loop:** Continues until a player wins or the game ends in a draw.
- **Player Turns:** Alternates between Player X and Player O using a boolean flag (`playerXTurn`).
- **Input Handling:** Uses `std::cin` to get row and column inputs from the players.
- **Win Checking:** Uses separate functions (`checkRows`, `checkCols`, `checkDiagonals`) to determine if there's a winning configuration.

### Improvements:
- **Input Validation:** Add robust input validation to handle non-numeric inputs and out-of-bound inputs.
- **Graphics:** Enhance the output with ASCII art or graphical representation of the board.
- **AI Player:** Implement an AI opponent using simple strategies (e.g., random moves or basic heuristic).

This basic implementation provides a functional Tic-Tac-Toe game that you can expand and enhance based on your requirements and creativity.
