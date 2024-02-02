# Pig Game

This project is a simple web-based implementation of the classic Pig Game, where two players take turns rolling a dice to accumulate points. The game continues until a player decides to hold their current score or rolls a 1.

## Table of Contents
- [Project Structure](#project-structure)
- [How to Play](#how-to-play)
- [Code Overview](#code-overview)
- [Contributing](#contributing)
- [License](#license)

## Project Structure
The project consists of three main files:
- **index.html:** The HTML file contains the structure of the game, including player sections, scores, current scores, dice image, and control buttons.
- **style.css:** The CSS file provides the styling for the game, defining the appearance and layout of the elements.
- **script.js:** The JavaScript file contains the logic for the Pig Game, handling user interactions, dice rolling, scoring, and player switching.

## How to Play
1. Open the `index.html` file in a web browser.
2. Two players take turns rolling a dice by clicking the "Roll Dice" button.
3. The current score is updated based on the dice roll, but if a player rolls a 1, their current score is reset, and it becomes the next player's turn.
4. Players can choose to "Hold" their current score, adding it to their total score. The first player to reach a predefined score threshold (currently set to 20) wins the game.
5. Click the "New Game" button to reset the game and start a new round.

## Code Overview
### HTML Structure
The HTML file (`index.html`) defines the game structure with player sections, scores, current scores, dice image, and control buttons.

### CSS Styling
The CSS file (`style.css`) provides styling to create an appealing and user-friendly interface for the game.

### JavaScript Logic
The JavaScript file (`script.js`) handles the game logic. Key functionalities include:
- Initializing the game state (`init` function).
- Rolling the dice and updating the current score.
- Holding the current score and switching to the next player.
- Checking for a winner and ending the game.
- Event listeners for user interactions with the roll, hold, and new game buttons.

## Contributing
If you'd like to contribute to the project, feel free to fork the repository, make changes, and submit a pull request. Issues and feature requests are also welcome.

## License
This Pig Game project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute the code for your own projects.
