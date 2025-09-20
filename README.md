# 🎮 Tic-Tac-Toe Game

A modern, interactive Tic-Tac-Toe game built with React that features game history tracking and move navigation.

![React](https://img.shields.io/badge/React-19.1.0-blue.svg)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow.svg)
![CSS3](https://img.shields.io/badge/CSS3-3.0-orange.svg)

## ✨ Features

- **Interactive Gameplay**: Play classic Tic-Tac-Toe with X and O players
- **Win Detection**: Automatically detects and announces the winner
- **Game History**: Complete move history tracking
- **Time Travel**: Jump back to any previous move in the game
- **Responsive Design**: Clean, modern UI that works on all devices
- **Real-time Status**: Shows current player turn and game status

## 🚀 Getting Started

### Prerequisites

- Node.js (version 14 or higher)
- npm (comes with Node.js)

### Installation

1. **Clone or download the project**
   ```bash
   git clone <your-repo-url>
   cd Tic-Tack-toe/Code
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm start
   ```

4. **Open your browser**
   Navigate to `http://localhost:3000` to play the game!

## 🎯 How to Play

1. **Start the Game**: The game begins with X's turn
2. **Make a Move**: Click on any empty square to place your mark
3. **Win Condition**: Get three marks in a row (horizontally, vertically, or diagonally)
4. **Game History**: Use the move list on the right to jump back to any previous move
5. **New Game**: Refresh the page to start a new game

## 🛠️ Available Scripts

- `npm start` - Runs the app in development mode
- `npm build` - Builds the app for production
- `npm test` - Launches the test runner
- `npm eject` - Ejects from Create React App (one-way operation)

## 📁 Project Structure

```
Code/
├── public/
│   └── index.html          # HTML template
├── src/
│   ├── App.js             # Main game component
│   ├── index.js           # React app entry point
│   └── styles.css         # Game styling
├── package.json           # Dependencies and scripts
└── README.md             # This file
```

## 🎨 Game Components

- **Square**: Individual game cell component
- **Board**: 3x3 grid containing 9 squares
- **Game**: Main container managing game state and history
- **Move History**: Sidebar showing all previous moves

## 🔧 Technical Details

- **Framework**: React 19.1.0 with Hooks
- **State Management**: useState for local state
- **Styling**: Pure CSS with flexbox layout
- **Build Tool**: Create React App

## 🚀 Future Enhancements

Here are some ideas for improving the game:

1. **Current Move Indicator**: Show "You are at move #..." for the current move
2. **Dynamic Board Generation**: Use loops instead of hardcoded squares
3. **Move Sorting**: Toggle between ascending/descending move order
4. **Win Highlighting**: Highlight winning squares when someone wins
5. **Draw Detection**: Display draw message when no one wins
6. **Move Coordinates**: Show (row, col) position for each move
7. **AI Opponent**: Add computer player with different difficulty levels
8. **Score Tracking**: Keep track of wins/losses across multiple games
9. **Sound Effects**: Add audio feedback for moves and wins
10. **Animations**: Smooth transitions and hover effects

## 🤝 Contributing

Feel free to fork this project and submit pull requests for any improvements!

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

**Happy Gaming! 🎮**