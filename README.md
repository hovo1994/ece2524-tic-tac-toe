# tic-tac-toe
python tic tac toe game
## getMove
- designed to get a valid nubmer from the user
- while loop repreats until valid number has been entered
- validate input with int() within a try 

## play()
- This is the main gameplay function. It is executed when the program starts up and prompts the player to make his/her first move. 
- The human player will always go first during gameplay and the players will alternate until someone plays a winning move

## generateMove()
- This function uses the helper function win_block to deterime if it can win or if it needs to block the human player from winning. If there is no wining or blocking availble it will generate a random move using the helper function randomMove.

## randomMove()
- This is the helper function for generating a random move. It uses the shuffle module to shuffle the list of moves and picks the top move from the list.

## win_block()
- This function checks to see if the AI can win the game or if it needs to block the human player from winning by going through each entry of the board and testing it out. If the AI can win or if it needs to block, then it sets the square in the board to 0 otherwise 

## swapPlayer(player)
- This function swaps the player's turn.

## getMove(player)
- This function takes in an input from the human player. 

## printBoard()
## checkWin(player, board)
## wipeBoard()
## canMove()