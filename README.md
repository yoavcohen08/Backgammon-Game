# Backgammon in Jack Language

This project is an implementation of the Backgammon game using the Jack programming language. The game is designed to run on the Nand2Tetris platform.

## Project Structure

The project consists of the following files:

- `Arrow.jack`: Implements the Arrow class for handling arrow movements.
- `Backgammon.jack`: Implements the main Backgammon game logic.
- `Board.jack`: Implements the Board class for managing the game board.
- `ChoiseZone.jack`: Implements the ChoiseZone class for handling choice zones.
- `Column.jack`: Implements the Column class for managing columns on the board.
- `Dice.jack`: Implements the Dice class for rolling dice.
- `EatZone.jack`: Implements the EatZone class for managing eaten pieces.
- `ListofPiece.jack`: Implements the ListofPiece class for managing a list of pieces.
- `Main.jack`: The entry point of the game.
- `OpeningScreen.jack`: Implements the OpeningScreen class for the game's opening screen.
- `Piece.jack`: Implements the Piece class for managing game pieces.
- `Random.jack`: Implements the Random class for generating random numbers.
- `WinZone.jack`: Implements the WinZone class for managing the winning zone.

## How to Run

1. Clone the repository to your local machine:
    ```sh
    git clone https://github.com/liramkreiner/Backgammon.git
    cd Backgammon
    ```

2. Open the Nand2Tetris software suite.

3. Load the project files into the Jack compiler:
    - Open the Jack Compiler.
    - Navigate to the directory where you cloned the repository.
    - Select all `.jack` files and compile them to VM code.

4. Load the VM code into the VM emulator:
    - Open the VM Emulator.
    - Load the compiled `.vm` files into the VM Emulator.

5. Run the emulator to play the game:
    - Click on the "Run" button in the VM Emulator to start the game.

## Game Instructions

1. The game starts with an opening screen where players are prompted to enter two seed numbers for the random number generator.
2. Players roll the dice to determine who starts the game.
3. Players take turns rolling the dice and moving their pieces according to the rules of Backgammon.
4. The game ends when one player has moved all their pieces to the winning zone.

## Authors

- Yoav Cohen
- Liram Kreiner

## License

This project is licensed under the MIT License.