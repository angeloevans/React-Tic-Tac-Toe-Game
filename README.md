# React Tic-Tac-Toe Game

## 🎮 Description

As part of my journey learning React, I explored this Tic-Tac-Toe tutorial, which helped me grasp key concepts like **state management**, **event handling**, **conditional rendering**, and **component structure**.

This simple **Tic-Tac-Toe** game allows two players to take turns marking "X" and "O" on a 3x3 grid. The game automatically detects a winner when a player aligns three marks in a row, column, or diagonal. Players can also view the history of their moves and jump back to any previous state in the game.

## 💡 Key Concepts Learned

Through this project, I reinforced my understanding of the following React concepts:

- **State Management**: Using the `useState` hook to manage the game’s state, such as player turns and the game history.
- **Component-based Architecture**: Breaking down the UI into reusable components (`Square`, `Board`, `Game`).
- **Handling Events**: Managing user interactions, like clicking a square, to update the game state.
- **Conditional Rendering**: Dynamically updating the UI to display the next player, a winner, or the history of moves.
- **Array manipulation**: Understanding how to handle a history of game moves with an array and update the state based on those moves.

## 🚀 Technologies Used

- **React**: For building the user interface and managing state.
- **JavaScript (ES6)**: For writing game logic and functional components.

## ⚙️ How to Run the Game Locally

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/react-tic-tac-toe.git
    ```

2. **Navigate to the project folder**:
    ```bash
    cd react-tic-tac-toe
    ```

3. **Install dependencies**:
    ```bash
    npm install
    ```

4. **Run the app**:
    ```bash
    npm start
    ```

5. Open your browser and visit [http://localhost:3000](http://localhost:3000) to play the game.

## 💻 How It Works

- **Game Component**: This is the main component that keeps track of the history of moves, the current move, and determines which player (X or O) is next.
- **Board Component**: This component contains the 3x3 grid of squares and handles the game logic for each square.
- **Square Component**: A button component that represents each square on the Tic-Tac-Toe board, which players can click to make a move.

### Game Flow

1. The game starts with an empty board.
2. Players take turns clicking on empty squares to place their mark ("X" or "O").
3. The game detects a winner when a player aligns three marks horizontally, vertically, or diagonally.
4. The status of the game (next player or winner) is displayed above the board.
5. Players can click on past moves to jump to that point in the game history.
