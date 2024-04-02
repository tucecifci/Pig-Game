# Pig-Game
Hello everybody! 👋 </br>
✨ Welcome to the Pig Game! This game is a simple dice game where players take turns rolling a dice and accumulating points. The objective of the game is to be the first player to reach a certain score, typically 100 points.
The Pig Game is a classic dice game that is both fun and easy to play. Each player takes turns rolling a six-sided die and adds the result to their current score. However, if a player rolls a 1, they lose all of their current points and their turn ends. The game continues until one player reaches the target score and wins the game.


## 👀 Overview

### 📷 Screenshot

![screencapture-tucecifci-github-io-Pig-Game-2024-04-02-20_08_09](https://github.com/tucecifci/Pig-Game/assets/151346784/9932b36d-8f2e-43d5-8aae-2f5068340d9b)
![screencapture-tucecifci-github-io-Pig-Game-2024-04-02-20_08_33](https://github.com/tucecifci/Pig-Game/assets/151346784/1d05ffdd-7bca-46c1-98ad-78fb0d3e7dd7)

![screencapture-tucecifci-github-io-Pig-Game-2024-04-02-20_09_39](https://github.com/tucecifci/Pig-Game/assets/151346784/f4b81a70-7aef-4708-8344-ad3b17c59f84)

### 🔗 Links

- https://tucecifci.github.io/Pig-Game/

## My process

### 💡 Built with

The Pig Game is built using the following technologies:

- HTML5: Used for structuring the webpage content and layout.
- CSS3: Used for styling the game interface, including colors, typography, and layout.
- JavaScript: Used for implementing the game logic, including dice rolling, turn management, and score calculation.

### 🧠 What I learned

While working on the Pig Game project, I learned:

- How to implement game logic using JavaScript.
- How to manipulate the DOM to create an interactive user interface.
- How to handle user input and respond to user actions.
- How to manage game state and track player scores.
- How to incorporate randomness and probability into game design.

```javascript
const switchPlayer = function () {
  document.getElementById(`current--${activePlayer}`).textContent = 0;
  currentScore = 0;
  activePlayer = activePlayer === 0 ? 1 : 0;
  player0El.classList.toggle('player--active');
  player1El.classList.toggle('player--active');
};
```
```javascript
  btnNew.addEventListener('click', init);
```



### 👩🏼‍💻 Features

The Pig Game offers the following features:

- Dice Rolling: Players can roll a six-sided die to accumulate points.
- Turn-Based Gameplay: Players take turns rolling the dice and making decisions.
- Point Accumulation: Players accumulate points with each successful roll.
- Risk and Strategy: Players must decide whether to continue rolling and risk losing their points or end their turn and bank their points.
- Win Condition: The game ends when one player reaches the target score and is declared the winner.


### 🤔 How to Play

To play the Pig Game:

1. Open the `index.html` file in your web browser.
2. Enter the target score (the score required to win the game).
3. Click the "Roll Dice" button to roll the dice and accumulate points.
4. Click the "Hold" button to bank your points and end your turn.
5. Avoid rolling a 1, as this will cause you to lose all of your current points and end your turn.
6. Continue playing until one player reaches the target score and wins the game.


### 🤌🏻 Useful resources

- https://www.udemy.com/course/the-complete-javascript-course/?couponCode=KEEPLEARNING
- https://developer.mozilla.org/en-US/docs/Web/API/DOMTokenList/toggle

### 🙏 Special Thanks
- Jonas Schmedtmann

## 🏳️‍🌈 Author

- Tuğçe Çifci - [@tucecifci](https://github.com/tucecifci)
- Frontend Mentor - [@tucecifci](https://www.frontendmentor.io/profile/tucecifci)
