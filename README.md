# tic-tac-toe-game

this is a simple tic-tac-toe game in c++.
for start, the code fills a 3 x 3 board with empty spaces, severed by | and + to represent a board [initializeBoard()].
the first player to mark is 'X'.

printBoard() function displays the current state of the board, wether it's empty or the players marked their positions.

isValidMove(int row, int col) function checks wether the currentPlayer marked withi the board's limits and that particular position is empty. if not, the function returns false and currentPlayer is asked for its input again.

checkWin() function checks the lines, columns and diagonals to see if those are filled by X or O. returns true when one of the conditions is fulfilled.

isBoardFull() function checks for empty spaces left in the board. if true, permits the players to mark until function returns false and the game is over. 

switchPlayer() function checks for the char of currentPlayer. if its X, then changes to O and vice-versa. 
