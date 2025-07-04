# Tic-Tac-Toe Game

A classic Tic-Tac-Toe game implemented in Python using Tkinter GUI library. This is a two-player game where players take turns marking spaces on a 3×3 grid with X's and O's.

## Features

- 🎮 Graphical User Interface using Tkinter
- 👥 Two-player gameplay
- 🔄 Game state tracking
- ⚡ Real-time turn indicators
- 🏆 Win/Draw detection
- 🔄 Restart game functionality

## Technologies Used

- Python 3
- Tkinter (GUI Library)

## Game Rules

1. The game is played on a 3x3 grid
2. Player 1 uses 'X' and Player 2 uses 'O'
3. Players take turns placing their marks in empty squares
4. The first player to get 3 marks in a row (horizontally, vertically, or diagonally) wins
5. If all squares are filled and no player has won, the game is a draw

## Screenshots

### Game Interface
The main game interface with a 3x3 grid and control buttons.

![Gui](https://user-images.githubusercontent.com/52067673/83345735-36b9e200-a334-11ea-942e-d9dda5586477.png)

### Winning Message
Display when a player wins the game.

![Winning_message](https://user-images.githubusercontent.com/52067673/83345776-7ed90480-a334-11ea-9fff-ddb43ca7401a.png)

### Draw Match Message
Display when the game ends in a draw.

![draw_messge](https://user-images.githubusercontent.com/52067673/83345796-9c0dd300-a334-11ea-8204-cb2611819a8a.png)

## How to Run

1. Make sure you have Python installed on your system
2. Clone this repository:
   ```bash
   git clone https://github.com/iabubakartahir/Tic-Tac-Toe-Game.git
   ```
3. Navigate to the project directory
4. Run the game:
   ```bash
   python tic-tac-toe.py
   ```

## Game Controls

- Click on any empty cell to place your mark (X/O)
- Use the 'Restart' button to start a new game
- The game status is displayed at the bottom
- Player indicators show whose turn it is

## Features Implementation

- **Turn Tracking**: The game automatically switches between Player 1 (X) and Player 2 (O)
- **Win Detection**: Checks for winning combinations after each move
- **Draw Detection**: Automatically detects when the game ends in a draw
- **Button Disabling**: Prevents moves after game completion
- **Visual Feedback**: Shows current player's turn and game results

## Contributing

Feel free to fork this repository and submit pull requests to contribute to this project. Any contributions, whether they are bug fixes or new features, are welcome!

## License

This project is open source and available under the [MIT License](https://opensource.org/licenses/MIT).
