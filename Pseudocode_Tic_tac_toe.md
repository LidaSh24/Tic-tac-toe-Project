1. Initialize a 3x3 board with empty spaces (or numbers for position reference).
2. Display the board.
3. Ask the first player to choose between 'X' and 'O'.
   - Assign the second player the opposite symbol.
4. Set the current player as the first player.
5. Repeat until there is a winner or the board is full:
   a. Display the board.
   b. Ask the current player to choose a position (1-9).
   c. Validate the input:
      - Check if the position is within range.
      - Check if the position is unoccupied.
   d. Place the player's symbol on the chosen position.
   e. Check if the current player has won:
      - If 3 symbols align in a row, column, or diagonal, declare them the winner.
      - End the game.
   f. If the board is full and no winner, declare a draw and end the game.
   g. Switch turns to the other player.
6. Display the final board and result.
#########################################################################################################
We have two option for players,
First player can choose to be either O or X player and the second player will be automatically assigned as the other symbol player,
1-Display the board game,
print 3*3 board game 
and assign numbers to each position 
2-Ask the first player to choose between X and O,

input=please choose between X and O

3-Then ask the player to assign a position for the choosen symbol,


4-Locate the symbol in the choosed position,

5-Ask the second player to choose a place for his move,

6-Repeat the process from step 3,

7-whenever 3 symbols of the same shape positioned in one row or column or digonally that symbol will be the winner 
 ##########################################################################################################