# Tic Tac Toe

## Introduction

This is a simulation of the game Tic Tac Toe. It currently fixes the players as X and O. In addition to this a game board is created that is used to places their corresponding X and O in the position they want. 

The project contains several different functions along with different function calls, which work to allow 2 users to play the game. 

**Clone the Repository**

```
git clone https://github.com/harshg28101999/Tic-Tac-Toe.git

```
**Launch the Game**

```
python3 tictac.py
```

## Flow of the Game

**Turn of the first player**

When the python app is run at first then it would be show the following results.
Here the game board is set up and asks for the position that the first players wants to play at.
```
 - | - | -
 - | - | -
 - | - | -
 X's turn
 Choose a position from 1-9: 

```

**Turn of the second player**

Say if the first player places 'X' at position 1. Then it would prompt 'O' to place their location on to the game board.
Moreorver, it would show X and replace the place position of '-' which indicates an empty space. 
```
 - | - | -
 - | - | -
 - | - | -
 X's turn
 Choose a position from 1-9: 1
 
 X | - | -
 - | - | -
 - | - | -
 O's turn
 Choose a position from 1-9: 
 
```
This goes till a winner is decided.

**Once a winner it decided and hence declares who th winner is**
```
 X | O | X
 O | X | O
 X | - | -
 X won.

```

## Future Enhancements

Some of the possible enhancements that could be made to this application would be:
* A function could be defined that would take the name of the players.
* Each player is given a choice if he/she wants to be 'X' or 'O'.
* A function could be defined to choose who goes first.






