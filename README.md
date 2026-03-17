# Rock Paper Scissors Game

An interactive Rock Paper Scissors game with score tracking and persistent data storage.

## 🎮 Features

- **Interactive Gameplay** — Click buttons to play against computer
- **Score Persistence** — Scores saved using localStorage
- **Visual Feedback** — Shows both player and computer moves with emojis
- **Win/Loss Tracking** — Tracks wins, losses, and ties
- **Reset Functionality** — Clear scores and start fresh
- **Responsive Design** — Clean UI with hover effects

## 🛠️ Technologies Used

- HTML5
- CSS3
- Vanilla JavaScript
- localStorage API

## 📂 Project Structure
```
rock-paper-scissors/
├── rpc.html           # Main HTML structure
├── rpc.css            # Styling
├── rpc.js             # Game logic and localStorage
└── images/            # Rock, paper, scissors emojis
```

## 🚀 How to Run

1. Clone this repository
2. Open `rpc.html` in your browser
3. Start playing!

## 🎯 Game Logic
```javascript
// Computer randomly selects move
const computerMove = pickComputerMove();

// Compare moves and determine winner
if (playerMove === 'rock' && computerMove === 'scissors') {
    result = 'You win!';
}

// Update scores and save to localStorage
localStorage.setItem('score', JSON.stringify(score));
```

## 💡 What I Learned

- DOM manipulation with querySelector
- Event handling with onclick
- localStorage for data persistence
- JSON.stringify and JSON.parse
- Game state management
- Conditional logic for game rules

## 📝 Future Improvements

- Add animations for moves
- Best of 5 rounds mode
- Sound effects
- Multiplayer option
- Difficulty levels (easy/hard computer AI)

## 👤 Author

**Maxpato**  
BCA Student | Full-Stack Developer  
📍 Mysuru, India

---

⭐ Star this repo if you found it helpful!
