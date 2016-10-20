## Tic Tac Toe

[Specification](#specification) |[Design](#design) | [Installation](#installation) | [Resources](#resources)

## Specification

The rules of tic-tac-toe are as follows:

* There are two players in the game (X and O)
* Players take turns until the game is over
* A player can claim a field if it is not already taken
* A turn ends when a player claims a field
* A player wins if they claim all the fields in a row, column or diagonal
* A game is over if a player wins
* A game is over when all fields are taken

Build the business logic for a game of tic tac toe. It should be easy to implement a working game of tic tac toe by combining your code with any user interface, whether web or command line.

## Design

Designed using Python 3.5.2 following Beck Design Principles.

Optional additions for computer logic:
- minimax algorithm
- alpha-beta pruning

Variable/Object    | Type  		| Comment
------------------ | -------------------	| ---------------------------
Player | String | current player
Action | Function | possible moves from current player
Result | Function | outcome after action
Terminal | Boolean | Has game reached a terminal state?
Utility | Number(int) | the consequence of an action for current player

Class    | Functions  	    	| Comment
------------------ | -------------------	| ---------------------------
TicTacToe | outcome() | win, loss or draw
Board | show() | displays board
Turn | move() | action

## Installation

Check you have python3 installed in your command line:
```$ python --version
```
Fork this repo or ```git clone``` this repo on your local machine.

Play the game in command line:
```$ python3 tic_tac_toe.py
```
Run the tests with pytest 3.0.3 in command line:
```$ pytest test_tic_tac_toe.py
```
- Check pytest version:
```$ pytest --version
```
## Resources

- Official Python docs https://docs.python.org/3/
- Python Program Design https://youtu.be/bbVkQ0evqzw
- AI with Tic Tac Toe http://rithinch.weebly.com/blog/artificial-intelligence-within-tic-tac-toe
