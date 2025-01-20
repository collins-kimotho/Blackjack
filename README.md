# Blackjack Game

Welcome to the Blackjack game! This is a simple implementation of the classic card game using HTML, CSS, and JavaScript.

## How to Play

1. **Objective**: The goal of the game is to get as close to 21 as possible without going over.
2. **Start Game**: Click the "START GAME" button to begin a new game. You will be dealt two cards.
3. **New Card**: Click the "NEW CARD" button to draw a new card if your sum is less than or equal to 20.
4. **Winning**: If your sum is exactly 21, you win with a Blackjack!
5. **Losing**: If your sum exceeds 21, you lose the game.

## Game Elements

- **Player**: The player starts with a name "Per" and 200 chips.
- **Cards**: The cards are represented by numbers. Face cards (Jack, Queen, King) are worth 10, and Aces can be worth 11.
- **Sum**: The sum of the player's cards is displayed.
- **Messages**: The game displays messages to guide the player.

## Project Structure

- `index.html`: The main HTML file that includes the structure of the game.
- `index.css`: The CSS file for styling the game.
- `index.js`: The JavaScript file that contains the game logic.
- `images/`: A directory containing images used in the game.
- `package.json`: The configuration file for managing dependencies and scripts.
- `vite.config.js`: The configuration file for Vite.

## Getting Started

To run the game locally, follow these steps:

1. Clone the repository.
2. Install the dependencies using `npm install`.
3. Start the development server using `npm run dev`.
4. Open your browser and navigate to `http://localhost:3000`.

## Dependencies

- [Vite](https://vitejs.dev/): A fast build tool for modern web projects.

## License

This project is licensed under the MIT License.