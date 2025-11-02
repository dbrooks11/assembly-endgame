# Assembly Endgame

A word guessing game with a programming-themed twist on the classic hangman format. Instead of drawing a hangman, incorrect letter guesses eliminate programming languages from the screen until all languages are gone and the game is lost.

## Description

Assembly Endgame challenges players to guess a hidden word by selecting letters. Each incorrect guess removes one programming language from the display. Players must guess the word before all programming languages are eliminated. This project demonstrates complex state management, conditional rendering, and game logic implementation using React.

## How to Play

1. A hidden word is displayed with blank spaces for each letter
2. Click on letters to make guesses
3. Correct guesses reveal the letter in the word
4. Incorrect guesses eliminate one programming language from the screen
5. Win by revealing the entire word before all languages are eliminated
6. Lose if all programming languages are removed before the word is guessed
7. Start a new game to play again

## Features

- Interactive letter selection interface
- Visual feedback for correct and incorrect guesses
- Programming language elimination mechanic
- Win and loss condition detection
- New game functionality
- Guess tracking system
- Disabled state for already guessed letters

## Technologies Used

- React
- JavaScript (ES6+)
- HTML5
- CSS3

## Installation

1. Clone the repository
```
git clone https://github.com/dbrooks11/assembly-endgame.git
```

2. Navigate to the project directory
```
cd assembly-endgame
```

3. Install dependencies
```
npm install
```

4. Start the development server
```
npm run dev
```

5. Open your browser and visit `http://localhost:3000`

## Learning Objectives

This project was built to practice and understand:

- Managing complex game state with useState
- Implementing game logic and win/loss conditions
- Using useEffect for side effects and game state monitoring
- Handling user interactions and button states
- Conditional rendering based on game progress
- Working with arrays and string manipulation
- Creating reusable React components

## Game Mechanics

- Players have a limited number of incorrect guesses based on the number of programming languages displayed
- Each wrong guess removes one language from the display
- Letters can only be guessed once
- The game ends when either the word is completely revealed or all languages are eliminated
