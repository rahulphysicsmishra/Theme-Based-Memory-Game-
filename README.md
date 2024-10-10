# 🧠 Memory Game 🎮

Welcome to the **Memory Game**! This is a fun and challenging game where players flip cards to match pairs. The game is built using **JavaScript**, **HTML**, and **CSS**, and it features three exciting themes: **Food**, **Animals**, and **Nature**. Choose a theme and test your memory skills! 🌟

## 🎥 Demo

Check out the live gameplay here: [YouTube Video](#) <[!-- Add your YouTube link here --](https://youtu.be/yIM-pBjg3j4)>

## 🚀 How It Works

The game is simple yet engaging. Here's how the process works:

1. **Theme Selection**: 
   - On the home page, the player selects one of the three available themes (Food, Animals, Nature). 
   - The theme choice is saved in the browser's `localStorage`, allowing the game to load theme-specific images for the cards.

2. **Shuffling the Cards**:
   - Once a theme is selected, the game board is generated by shuffling the cards in random order. 
   - Each card starts face-down, displaying a blank image.

3. **Gameplay**:
   - The player clicks on two cards to reveal their images. If the images match, the cards stay flipped; if not, they flip back after a brief pause. 
   - The game keeps track of the matches and updates the score accordingly.

4. **Winning the Game**:
   - The game ends when all pairs of cards have been successfully matched. A congratulatory message appears once all pairs are found.

5. **Restart Option**:
   - After completing the game, players can click the "Restart Game" button to choose a different theme and play again!

## 🎯 Features

- **Three Fun Themes**: 
  - 🥗 **Food**: Fries, pizza, cheeseburgers, and more!
  - 🦁 **Animals**: Lions, elephants, tigers, etc.
  - 🌿 **Nature**: Trees, mountains, rivers, and more!
  
- **Dynamic Board Creation**: The cards shuffle randomly every time you play, making each game unique.

- **Smooth Animations**: Cards flip with a smooth transition for an engaging experience.

- **Responsive Design**: Works great on desktop.

## 🛠️ How the Game Was Built

This game was built using the following technologies:

- **HTML**: To structure the web pages.
- **CSS**: For styling, creating a responsive and interactive user interface.
- **JavaScript**: To handle the game logic, including flipping cards, checking for matches, and shuffling.

### 📂 Folder Structure:

```
memory-game/
│
├── index.html         # Home page where players select a theme
├── grid.html          # Game page where the card grid is displayed
├── memory.css         # Stylesheet for the game
├── memory.js          # Main game logic script
└── images/            # Folder containing images for cards
```

### ✨ Key Steps in Development:

1. **Set up the HTML files**:
   - `index.html`: Includes a welcome message, theme selection, and a button to start the game.
   - `grid.html`: Displays the shuffled card grid and the score.
   
2. **CSS Styling**:
   - Styled the grid to make it responsive and visually appealing.
   - Added hover effects to cards and buttons to make the game interactive and engaging.

3. **JavaScript Game Logic**:
   - Implemented the card flipping logic in `memory.js`.
   - Used `localStorage` to remember the player's theme selection across pages.
   - Implemented the matching mechanism, updating the score, and a restart button.

## 🛠️ Getting Started

### Prerequisites:

To run this game locally, all you need is a web browser.

### Installation:

1. Clone the repository to your local machine:

   ```
   gh repo clone rahulphysicsmishra/Theme-Based-Memory-Game-
   ```

2. Open the project folder and launch the game by opening the `index.html` file in your browser.

3. Start playing by selecting a theme and flipping cards!

## 🔥 Contributing

If you'd like to contribute to improving the game, feel free to submit a pull request or open an issue! Contributions are welcome.
