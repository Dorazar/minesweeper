# 💣 Mine Sweeper Game
<img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/c84553f7-1634-4516-9c7d-9d2598275267" />

A modern, feature-rich implementation of the classic Minesweeper game with special power-ups and multiple difficulty levels.

## 🎮 Live Demo

[Play the game here](https://dorazar.github.io/minesweeper/) <!-- Add your deployed URL -->

## ✨ Features

### Core Gameplay
- **Classic Minesweeper mechanics** - Left click to reveal cells, right click to mark mines
- **Three difficulty levels**:
  - Beginner (8×8 grid, 14 mines)
  - Medium
  - Expert
- **Lives system** - 3 lives to spare before game over
- **Timer** - Track your best times
- **Score tracking** - Best scores saved for each difficulty level

### Special Power-ups
- **💡 Hints** (3 available) - Reveal a cell and its neighbors temporarily
- **🔍 Mega Hint** (1 available) - Select two corners to reveal an entire area
- **🧹 Mine Exterminator** (1 available, Medium/Expert only) - Remove a random mine
- **🏝️ Safe Click** (3 available) - Highlights a safe cell
- **⏮️ Undo** (3 available) - Undo your last move

### User Experience
- **Responsive design** - Works on desktop and mobile devices
- **Touch support** - Long press on mobile to mark cells
- **Light/Dark mode** - Toggle between themes
- **Tutorial** - Interactive guide for new players
- **Animations** - Smooth transitions and visual feedback

## 🚀 Getting Started

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Dorazar/minesweeper-game.git
```

2. Navigate to the project directory:
```bash
cd minesweeper-game
```

3. Open `index.html` in your browser or use a local server:
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve
```

4. Navigate to `http://localhost:8000` in your browser

## 🎯 How to Play

1. **Left Click** - Reveal a cell
2. **Right Click** - Mark/unmark a cell as a mine
3. **Mobile** - Long press to mark cells
4. Choose your difficulty level and click a cell to start
5. Use power-ups strategically to help you win
6. Clear all safe cells without hitting all mines to win!

### Winning Condition
Reveal all non-mine cells or correctly mark all mines with only 1 or fewer mistakes.

## 🛠️ Technologies Used

- **HTML5** - Structure
- **CSS3** - Styling with animations
- **Vanilla JavaScript** - Game logic (no frameworks!)
- **Google Analytics** - Usage tracking

## 📁 Project Structure

```
├── index.html          # Main HTML file
├── css/
│   └── app.css        # Styles and animations
├── js/
│   ├── game.js        # Core game logic
│   ├── stopwatch.js   # Timer and score management
│   └── utils.js       # Helper functions
├── jpg/               # Images and assets
└── README.md          # This file
```

## 🎨 Features Breakdown

### Game Modes
- **Beginner** - Perfect for learning the game
- **Medium** - Moderate challenge with all power-ups
- **Expert** - Maximum difficulty for experienced players

### Power-up System
Each power-up has limited uses and adds strategic depth:
- Plan your moves carefully
- Save power-ups for difficult situations
- Combine them effectively to maximize your chances

## 📊 Score System

Your best completion time for each difficulty level is automatically saved and displayed in the score table.

## 🤝 Contributing

Contributions are welcome! Feel free to:
1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is part of Coding Academy coursework.

## 👤 Author

DorAzar
- GitHub: https://github.com/Dorazar

## 🙏 Acknowledgments

- Coding Academy for the project guidelines
- Classic Minesweeper for game inspiration

---

**Enjoy playing! May your clicks be safe and your flags be accurate! 🎯**
