# TicTacToe
Simple command line Tic-Tac-Toe game making use of 2d arrays, for loops, while loops, switch statements, and ArrayLists (among other things).

This program allows you to take on the CPU in a game of Tic-Tac-Toe.

Used a 2d char array to display the game board on the command line.
The player's moves are selected using the 1-9 keys to correspond with the spaces on the game board. /n
The CPUs moves are randomized using Random(). **Goal is to eventually add a simple AI to make the games more challenging and less dependent on RNG**
After each move, the game board is checked against an ArrayList that is populated with the 8 possible win conditions.
If any of the 8 win conditions are met, a message is printed to the command line with the result of the match, and the program exits.
