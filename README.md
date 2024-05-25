# Customizable Tic-Tac-Toe Game

This project is a customizable Tic-Tac-Toe game built with React. Users can define the size of the grid (n x n) and the number of consecutive marks (m) required to win the game. The game has a clean, simple, and intuitive user interface and is responsive on both desktop and mobile devices.

## Features

- **Customizable Grid Size**: Users can set the grid size (n x n), where n is any integer between 3 and 10.
- **Customizable Win Streak**: Users can set the win streak (m), where m is any integer between 3 and n.
- **User Interface**: The game has a clean and simple UI.
- **Game Logic**: Handles turns, checks for a win or draw, and displays the result.
- **Responsiveness**: The game is playable on both desktop and mobile devices.

## Getting Started

### Prerequisites

- Node.js and npm (Node Package Manager) installed on your local machine.

### Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/Vikassinghrathor/Wyb_Assignment_TicTacToe.git
    ```
2. **Navigate to the project directory:**
    ```bash
    cd customizable-tic-tac-toe
    ```
3. **Install dependencies:**
    ```bash
    npm install
    ```

### Running the Application

1. **Start the development server:**
    ```bash
    npm start
    ```
2. Open your browser and go to `http://localhost:3000` to see the application in action.

## Usage

1. **Set Grid Size**: Use the input field labeled "Grid Size" to set the size of the grid (n x n). The value should be an integer between 3 and 10.
2. **Set Win Streak**: Use the input field labeled "Win Streak" to set the number of consecutive marks needed to win. The value should be an integer between 3 and the grid size (n).
3. **Play the Game**: Click on the tiles to make your move. The game alternates between Player X and Player O.
4. **Check Result**: The game will automatically check for a win or draw and display the result.
5. **Reset Game**: Click the "Play Again" button to reset the game.

## Project Structure

- `src/components`
  - `TicTacToe.js`: Main component containing the game logic and state management.
  - `Board.js`: Component responsible for rendering the game board.
  - `Tile.js`: Component for individual tiles on the board.
  - `Strike.js`: Component for displaying the winning strike line.
  - `GameOver.js`: Component for displaying the game result.
  - `Reset.js`: Component for resetting the game.
  - `GameState.js`: Enum for managing game states.

## Styles

The game uses CSS for styling, located in the `src/App.css` file. Adjustments are made to ensure the board is responsive and visually appealing.

## Sounds

The game includes sounds for tile clicks and game over. These are located in the `src/sounds` directory.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Inspired by classic Tic-Tac-Toe games.
- Built with React.


