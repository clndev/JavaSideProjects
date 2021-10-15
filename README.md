# TicTacToe
Simple command line Tic-Tac-Toe game that allows you to take on the CPU. Utilizing 2d arrays, for loops, while loops, switch statements, and ArrayLists (among other things).

- Uses a 2d char array to display the game board on the command line

- The player's moves are selected using the 1-9 keys to correspond with the spaces on the game board

- The CPUs moves are randomized using Random()

- After each move, the game board is checked against an ArrayList that is populated with the 8 possible win conditions

- If any of the 8 win conditions are met, a message is printed to the command line with the result of the match, and the program exits

**FUTURE PLANS FOR THIS PROGRAM**
- Implement a simple AI to make the games more fun and less dependent on RNG (no real strategy is involved in playing as of right now)
- Clean up the main method in the code by making use of OOP principles to hide some of the clutter
- Add the ability to choose game mode: 1-player vs the CPU or PvP alternating turns on the same keyboard
- Introduce some variability by allowing the player(s) to choose a single game, best-of-3, best-of-5, etc.
