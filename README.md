# tic-tac-toe
A simple implementation of tic-tac-toe in Python 2, in which the user faces off against an AI opponent;

## Getting Started
### Requirements
- Python 2.7
- tictactoe.py file

### Installing
- Clone repository (No additional installation necessary)

## Running
- Navigate to folder where repository is stored
- Run command: python2 tictactoe.py

## How to Play
After running command above, player types in number corresponding with a certain location on the board and presses enter. The AI then counteracts the move with the location it chooses.
### Gameplay
- The game starts out with the following screen showing the game board locations with their corresponding numbers.
<code>

Tc Tac Toe
play against the computer AI level 0
one player
| 1 | 2 | 3 |
-------------
| 4 | 5 | 6 |
-------------
| 7 | 8 | 9 |
Square to place the X 

</code>

## Built With
Python v2.7

## Authors
- Hovhannes Avagyan (hovo1994)
- Wayne Thompson (dubiousFrog)

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
- designed to get a valid nubmer from the user
- while loop repreats until valid number has been entered
- validate input with int() within a try 

## printBoard()
- Creates the game board by looping through preset values and printing onto terminal

## checkWin(player, board)
- Checks for a winning combination

## wipeBoard()
- Resets board for new game

## canMove()
- Checks to see if the desired location of the AI's move is an empty space
- Iteratively checks each of the possible move locations for an empty space