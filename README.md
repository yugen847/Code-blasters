this project is to create a tic tac toe game where 3 users can play xox game .. 
RULES of This game:
    
  Game Objective:
Two players take turns to place their marks (either 'X' or 'O') on the 3x3 grid.
The first player to get three of their marks in a row (horizontally, vertically, or diagonally) wins the game.

  Gameplay:
Player 1 uses the 'X' symbol, and Player 2 uses the 'O' symbol.
Players alternate turns to choose a cell on the grid to place their mark.
The cells on the grid are numbered 0, 0 to 2, 2 (i.e., from 0 to 2 for both rows and columns). For example:
0 0 | 0 1 | 0 2
1 0 | 1 1 | 1 2
2 0 | 2 1 | 2 2
Players must input the row and column number where they want to place their mark (both row and column numbers are between 0 and 2).
               
  Turn Rules:
On each turn, the current player enters the row and column of an empty space on the board where they want to place their mark.
If the player tries to place their mark in a space that is already taken, the program will ask the player to choose a different space.

  Winning the Game:
A player wins by having three of their marks (either 'X' or 'O') in a row:
    Horizontally: All three marks are in one row (e.g., 0,0, 0,1, 0,2).
    Vertically: All three marks are in one column (e.g., 0,0, 1,0, 2,0).
    Diagonally: All three marks are in one of the two diagonals (e.g., 0,0, 1,1, 2,2 or 0,2, 1,1, 2,0).
Once a player wins, the game will announce the winner.

  Draw Condition:
If all the cells are filled and no player has won, the game ends in a draw.

   Game End:
The game ends either when:
One player wins by completing a row, column, or diagonal with their mark.
The board is full with no winner, resulting in a draw.

   Switching Turns:
After each turn, the player switches. If Player 1 is 'X', Player 2 will be 'O', and vice versa. This alternation continues throughout the game.
