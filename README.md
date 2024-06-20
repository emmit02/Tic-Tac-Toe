# Tic-Tac-Toe
This is a simple console-based Tic-Tac-Toe game implemented in Java. Two players take turns to place their marks ('X' or 'O') on a 3x3 grid. The game checks for a win condition after each move and declares the winner or a tie when appropriate.

Features
Two-player mode
Simple text-based user interface
Game board displayed after each move
Win, lose, and draw detection
How to Run
Clone the Repository

sh
Copy code
git clone https://github.com/emmit02/Tic-Tac-Toe.git
cd tic-tac-toe
Compile the Java Files

Ensure you have Java installed on your system. Open a terminal or command prompt and navigate to the project directory. Then, compile the Java files using the following command:

sh
Copy code
javac TicTacToe.java Main.java
Run the Game

After compilation, run the game using the following command:
https://github.com/emmit02/Tic-Tac-Toe.git
sh
Copy code
java Main
Game Instructions
The game starts with an empty 3x3 grid.
Player 'X' goes first and is prompted to enter the row and column where they want to place their mark. Rows and columns are indexed from 0 to 2.
After 'X' makes their move, the updated game board is displayed.
Player 'O' then takes their turn in the same manner.
The game continues until one player wins or the board is full, resulting in a tie.
Code Structure
TicTacToe.java
This file contains the Main class with the main method that runs the game loop.

Prompts the players for their moves.
Updates and prints the game board after each move.
Checks for a win or tie condition.
Switches players after each valid move.
Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your changes.

Enjoy playing Tic Tac Toe!
