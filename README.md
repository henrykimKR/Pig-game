# Pig Game Readme 🎲

Welcome to the Pig Game project! This is a simple web-based implementation of the classic Pig Game, designed to help beginners learn JavaScript techniques. Let's roll into the details! 🚀

## 🛠️ Project Structure
The project structure consists of three main files:

- **index.html:** Defines the game structure, including player sections, scores, current scores, dice image, and control buttons.

- **style.css:** Provides styling for an attractive and user-friendly interface.

- **script.js:** Contains the JavaScript logic for the Pig Game, handling user interactions, dice rolling, scoring, and player switching.

## 🎮 How to Play
1. Open `index.html` in a web browser.
2. Players take turns rolling a dice with the "Roll Dice" button.
3. Current score updates based on the dice roll, but rolling a 1 resets the score.
4. "Hold" adds the current score to the total; first to reach the target score (currently 20) wins.
5. Click "New Game" to start a new round.

## 🧠 JavaScript Techniques
### 1. **Event Listeners & Functions**
   - Event listeners capture user clicks on buttons like "Roll Dice" and "Hold."
   - Functions like `init`, `switchPlayer`, and event callback functions handle game logic.

### 2. **DOM Manipulation**
   - Selecting elements with `document.querySelector` and `document.getElementById`.
   - Updating text content and CSS classes with `textContent` and `classList`.

### 3. **Random Number Generation**
   - Generating random dice rolls using `Math.trunc(Math.random() * 6) + 1`.

### 4. **Conditional Statements**
   - Using `if` and `else` statements to check for conditions, such as rolling a 1 or reaching the target score.

### 5. **Toggling Classes**
   - Utilizing `classList.toggle` to switch active player classes and highlight the current player.

### 6. **Function Declarations & Expressions**
   - Declaring functions using both the traditional function declaration (`function init() {...}`) and function expressions (`const switchPlayer = function() {...}`).

### 7. **Variables & Arrays**
   - Declaring variables (`let`, `const`) for scores, current score, active player, and arrays to store scores.

### 8. **Embracing Emoticons!**
   - Injecting a touch of fun with emoji emoticons in buttons and headers. 🎉

## 🤝 Contributing
Feel free to contribute! Fork the repository, make changes, and submit a pull request. Issues and feature requests are also welcome.
