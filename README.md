# Tic-Tac-Toe Game

A classic Tic-Tac-Toe game built with HTML, CSS, and JavaScript. This interactive web-based game allows two players to play the timeless game of Xs and Os.

## 🎮 Features

- **Two-Player Mode**: Play with a friend on the same device
- **Winner Detection**: Automatically detects when a player wins
- **Draw Detection**: Identifies when the game ends in a draw
- **Reset Functionality**: Reset the game at any time with the reset button
- **New Game**: Start a fresh game after a winner is declared
- **Responsive Design**: Clean and centered layout that works on different screen sizes
- **Visual Feedback**: Color-coded game board with smooth styling

## 📁 Project Structure

```
Tic-Tac-Game/
├── index.html      # Main HTML structure
├── style.css       # Styling and layout
├── app.js          # Game logic and interactions
└── README.md       # Project documentation
```

## 🚀 Getting Started

### Prerequisites 

- A modern web browser (Chrome, Firefox, Safari, Edge, etc.)

### Installation

1. Clone or download this repository:

   ```bash
   git clone <repository-url>
   ```

2. Navigate to the project directory:

   ```bash
   cd Tic-Tac-Game
   ```

3. Open `index.html` in your web browser:
   - Double-click the `index.html` file, or
   - Right-click and select "Open with" your preferred browser

## 🎯 How to Play

1. **Start the Game**: Open the game in your browser
2. **Player O** goes first (automatically assigned)
3. **Take Turns**: Click on any empty box to place your mark (O or X)
4. **Win Condition**: Get three of your marks in a row (horizontally, vertically, or diagonally)
5. **Draw**: If all 9 boxes are filled without a winner, the game is a draw
6. **Reset**: Click the "Reset Game" button to start over at any time
7. **New Game**: After a game ends, click "New Game" to play again

## 🛠️ Technology Stack

- **HTML5**: Structure and layout
- **CSS3**: Styling with flexbox for responsive design
- **JavaScript (ES6)**: Game logic and interactivity

## 🎨 Design Highlights

- **Color Scheme**:
  - Background: Teal (`#548687`)
  - Game boxes: Light yellow (`#ffffc7`)
  - Text: Red (`#b0413e`)
  - Buttons: Dark gray (`#191913`)
- **Responsive**: Uses viewport units (vmin) for consistent sizing
- **Modern UI**: Rounded corners, shadows, and clean typography

## 📝 Game Logic

The game implements:

- **8 winning patterns**: All possible combinations to win
- **Turn-based system**: Alternates between Player O and Player X
- **Move counter**: Tracks total moves to detect draws
- **Board state validation**: Checks for winners after each move
- **Disable mechanism**: Prevents clicking on already-filled boxes

## 🔧 Customization

You can easily customize the game by modifying:

- **Colors**: Edit the CSS variables in `style.css`
- **Box size**: Adjust the `height` and `width` values in the `.box` class
- **Font size**: Change the `font-size` property
- **Win patterns**: Modify the `winPatterns` array in `app.js` (for custom board sizes)

## 📄 License

This project is open source and available for educational purposes.

## 👥 Contributing

Feel free to fork this project and submit pull requests with improvements or bug fixes.

## 🐛 Known Issues

None at this time. If you find any bugs, please report them!

---

Enjoy playing Tic-Tac-Toe! 🎉
