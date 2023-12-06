# Connect4 Game

Welcome to the Connect4 game repository! This simple console-based Connect4 game is implemented in Java. It allows two players to take turns making moves until one of them wins or the game ends in a tie.

## How to Play

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/racheldennis/connect4-game.git

2. Compile the Java files:
    ```bash
    javac *.java
    
3. Run the game:

      * ```bash
         java Runner_AI
      OR
     * ```bash
       java Runner_Human
    
3. Follow the on-screen instructions to make your moves.

## Project Structure

  * `Board.java`: Defines the game board and related operations.
  * `Player.java`: Abstract class representing a player with common attributes and methods.
  * `HumanPlayer.java`: Implements a human player who can make moves through console input.
  * `AIPlayer.java`: Implements an AI player with a basic strategy for making moves.
  * `ConnectFour.java`: Manages the overall flow of the Connect4 game.
  * `Runner_Human.java`: Entry point for running the game with two human players.
  * `Runner_AI.java`: Entry point for running the game with one human player and one AI player.

## Customize Players

You can customize player names, symbols, and strategies by modifying the `Runner_Human` and `Runner_AI classes`.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Feel free to contribute, report issues, or provide feedback. Enjoy the game!

