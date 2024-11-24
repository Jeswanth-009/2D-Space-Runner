# 2D-Space-Runner
# Runner Game

## Overview
The **Runner Game** is a simple, browser-based game where a player controls a character that can jump and shoot. The objective is to avoid obstacles and destroy enemies to score points. The game features three difficulty levels: Easy, Medium, and Hard, which adjust the speed of enemies and obstacles and the spawn rate of new elements.

## Features
- **Dynamic difficulty levels**: Easy, Medium, and Hard.
- **Player controls**: Jump to avoid obstacles and shoot to destroy enemies.
- **Scoring system**: Gain points by destroying enemies.
- **Game over handling**: Restart the game with a single button click.
- **Animations**: Includes explosions for visual effects when an enemy is hit.

---

## Project Files
- **index.html**: Contains the game structure and JavaScript logic.
- **style.css**: Embedded in the HTML for the game's styling.
- **player.png**: Image for the player's character.
- **enemy.png**: Image for enemies.
- **obstacle.png**: Image for obstacles.

---

## Setup Instructions
1. Download or clone the repository to your local machine.
2. Place all required images (`player.png`, `enemy.png`, `obstacle.png`) in the same directory as the HTML file.
3. Open the `index.html` file in any modern web browser to start the game.

---

## Controls
- **Spacebar**: Makes the player jump.
- **Enter**: Shoots bullets from the player.

---

## Game Logic
### Player Actions
- **Jump**: The player character jumps upwards with gravity pulling it back down. Prevents mid-air jumps.
- **Shoot**: Fires bullets that travel horizontally to destroy enemies.

### Difficulty Levels
- **Easy**: Slow enemy and obstacle speed; longer spawn intervals.
- **Medium**: Moderate enemy and obstacle speed; shorter spawn intervals.
- **Hard**: Fast enemy and obstacle speed; very short spawn intervals.

### Scoring
- Destroying an enemy adds 10 points to the score.

### Game Over
- Collision with an enemy or obstacle ends the game.
- Restart the game by clicking the "Restart" button.

---

## Customization
1. **Change Background**: Modify the `background` property in the CSS `#gameContainer` section.
2. **Adjust Gravity**: Change the `gravity` value in the JavaScript section to alter jump mechanics.
3. **Difficulty Settings**: Update the `difficulties` object to customize spawn rates and speeds for each level.
4. **Assets**: Replace `player.png`, `enemy.png`, and `obstacle.png` with custom images for a personalized look.

---

## Requirements
- A modern web browser (Google Chrome, Mozilla Firefox, Microsoft Edge, etc.).
- Images: `player.png`, `enemy.png`, `obstacle.png` (Add these to the project folder).

---

## Future Improvements
- Add power-ups for the player.
- Introduce multiple levels or themes.
- Include background music and sound effects.
- Implement a high-score leaderboard.

---

## License
This project is open-source and free to use. You can modify it as per your requirements.
