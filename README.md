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
- Run command: $python2.7 tictactoe.py

## How to Play
After running command above, player types in number corresponding with a certain location on the board and presses enter. The AI then counteracts the move with the location it chooses.

## Built With
Python v2.7

## Authors
- Hovhannes Avagyan (hovo1994)
- Wayne Thompson (dubiousFrog)

## getMove
- designed to get a valid nubmer from the user
- while loop repreats until valid number has been entered
- validate input with int() within a try 

## play()

## generateMove()
## randomMove()
## canIwin()
## canYouWin()
## win_block():
## generateMove()
## swapPlayer(player)
## getMove(player)
## printBoard()
- Creates the game board by looping through preset values and printing onto terminal

## checkWin(player, board)
- Checks for a winning combination

## wipeBoard()
- Resets board for new game

## canMove()
- Checks to see if the desired location of the AI's move is an empty space
- Iteratively checks each of the possible move locations for an empty space