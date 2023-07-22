# TicTacToe-Game
Certainly! Below is the TicTacToe game implemented in Java, formatted as a README file:

# TicTacToe Game in Java

This is a simple implementation of the classic TicTacToe game in Java. It allows two players to take turns and play on a 3x3 grid.

## How to Play

1. Open a Java IDE or command-line environment to run the game.

2. When the game starts, an empty 3x3 grid will be displayed.

3. Players will take turns to enter their moves on the grid.

4. Each player is represented by either 'X' or 'O'.

5. To make a move, players need to enter the row and column indices of their desired cell (0 to 2) through the console.

6. The game will check if the chosen cell is empty. If it is, the player's move will be placed on the grid.

7. The game will continue until one of the players wins or the entire board is filled, resulting in a draw.

8. If a player manages to get three of their symbols in a row (horizontally, vertically, or diagonally), they win the game.

## Running the Game

1. Copy the Java code provided in the `Main.java` file.

2. Paste the code into a Java IDE or a text editor.

3. Save the file with the name `Main.java`.

4. Compile and run the program to start the TicTacToe game.

## Example Gameplay

```
-------------
|   |   |   |
-------------
|   |   |   |
-------------
|   |   |   |
-------------

Player X enter: 1 1

-------------
|   |   |   |
-------------
|   | X |   |
-------------
|   |   |   |
-------------

Player O enter: 0 0

-------------
| O |   |   |
-------------
|   | X |   |
-------------
|   |   |   |
-------------

Player X enter: 0 1

-------------
| O | X |   |
-------------
|   | X |   |
-------------
|   |   |   |
-------------

Player O enter: 2 0

-------------
| O | X |   |
-------------
|   | X |   |
-------------
| O |   |   |
-------------

Player X enter: 0 2

-------------
| O | X | X |
-------------
|   | X |   |
-------------
| O |   |   |
-------------

Player O enter: 1 0

-------------
| O | X | X |
-------------
| O | X |   |
-------------
| O |   |   |
-------------

Player O has won!
```

Enjoy playing TicTacToe with a friend!
