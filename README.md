# 🎮 Tic Tac Toe Game - Built with React JS

[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactjs.org/)
[![Vite](https://img.shields.io/badge/Vite-B73BFE?style=for-the-badge&logo=vite&logoColor=FFD62E)](https://vitejs.dev/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

A modern, responsive, and interactive Tic Tac Toe game built with React JS. This project showcases fundamental React concepts including state management, component lifecycle, and event handling in a fun and engaging way.

## 🎯 Features

- **Interactive Gameplay**: Smooth and responsive Tic Tac Toe board
- **Turn-based System**: Alternates between X and O players automatically
- **Win Detection**: Automatically detects wins and displays the winner
- **Responsive Design**: Works on various screen sizes
- **Visual Feedback**: Clear indication of the current player's turn
- **Reset Functionality**: Easy game reset with a single click
- **Modern UI**: Clean and intuitive user interface with smooth animations

## 🚀 Demo

[Live Demo](#) *(Add your deployment link here)*

## 🛠️ Technologies Used

- **Frontend**: React JS
- **Build Tool**: Vite
- **Styling**: CSS3
- **Version Control**: Git

## 📦 Prerequisites

Before you begin, ensure you have the following installed:

- Node.js (v14 or higher)
- npm (v6 or higher) or Yarn
- Git (for version control)

## 🚀 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/Tic-Tac-Toe-Game-By-React-JS.git
   cd Tic-Tac-Toe-Game-By-React-JS
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   # or
   yarn dev
   ```

4. **Open in browser**
   The application should automatically open in your default browser at `http://localhost:5173`

## 🎮 How to Play

1. The game starts with Player X's turn
2. Click on any empty cell to place your mark (X or O)
3. Players alternate turns automatically
4. The first player to get 3 marks in a row (horizontally, vertically, or diagonally) wins
5. If all cells are filled without a winner, the game ends in a draw
6. Click the "Reset" button to start a new game at any time

## 🧩 Project Structure

```bash
src/
├── Components/           # React components
│   ├── TicTacToe.jsx    # Main game component
│   └── TicTacToe.css    # Game styling
├── assets/              # Static assets (images, icons)
├── App.jsx              # Root component
├── main.jsx             # Application entry point
└── index.css            # Global styles
```

## 🛠️ Key Implementation Details

- **State Management**: Uses React's `useState` hook to manage game state
- **Refs**: Utilizes `useRef` for direct DOM manipulation of game cells
- **Conditional Rendering**: Dynamically updates the UI based on game state
- **Event Handling**: Implements click handlers for game interactions
- **Responsive Design**: CSS Grid and Flexbox for responsive layouts

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a new branch: `git checkout -b feature/your-feature-name`
3. Make your changes and commit them: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin feature/your-feature-name`
5. Submit a pull request


## 🙏 Acknowledgments

- Built with ❤️ using React
- Inspired by classic Tic Tac Toe game
- Special thanks to the React community for amazing documentation and resources


