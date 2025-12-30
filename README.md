# Pig Game

A simple two-player dice game built using HTML, CSS, and JavaScript, where players take turns rolling a dice and accumulating points. The first player to reach the winning score wins the game.

This project focuses on DOM manipulation, game logic, and event handling in JavaScript.

## Game Rules

1. The game has 2 players, playing in turns.

2. On a player’s turn:

- Clicking Roll Dice generates a random number between 1 and 6.

- If the dice shows 1:

 - The player loses their current score.

 - The turn switches to the other player.

- If the dice shows 2–6:

 - The value is added to the player’s current score.

3. Clicking Hold:

- Adds the current score to the player’s total score.

- The turn switches to the other player.

- The first player to reach 25 points wins the game.

4. Clicking New Game resets the game to the initial state.

### Game Logic Flow

![Pig Game Flowchart](pig-game-flowchart.png)

### Tech Stack

- HTML5 – Structure of the game UI 

- CSS3 – Styling and layout 

- JavaScript (ES6) – Game logic and interactivity

## How to Run the Project

- Clone the repository:
  git clone https://github.com/your-username/pig-game.git

- Open index.html in your browser
      OR
  Use VS Code Live Server for a better experience.

## Features

- Interactive UI with animations

- Dice image updates dynamically

- Active player highlighting

- Winning state styling

- Reset game functionality

## What I Learned

- DOM selection and manipulation

- Event listeners (click events)

- Managing game state with variables

- Conditional logic and functions

- Writing clean and reusable JavaScript code

## Future Improvements

- Add customizable winning score

- Add sound effects

- Make it responsive for mobile

- Add single-player mode vs computer

## Author

Bosu Babu Bade
Aspiring Full Stack / Frontend Developer
