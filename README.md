# Blackjack Game

Welcome to the JavaScript Blackjack game! This is a simple implementation of the classic casino card game, where you can try your luck and see if you can beat the dealer.

## Getting Started

To run the game, open the `index.html` file in your web browser. The game interface will be displayed, and you can start playing.

## Game Rules

The goal of Blackjack is to have a hand value as close to 21 as possible without exceeding it. Each card has a specific value:

- Number cards (2-10) have their face value.
- Face cards (Jack, Queen, King) have a value of 10.
- Ace can have a value of either 1 or 11, depending on which value gives you a better hand.

## How to Play

1. When you start the game, you will be dealt two random cards. Your current hand total will be displayed as "Sum" on the screen.

2. If the total of your initial hand is 21, you've got Blackjack! You win the game.

3. If your total is below 21, you have the option to "draw a new card." This means you can request an additional card to be added to your hand. Click the "Draw a New Card" button to get a new card.

4. Be careful not to exceed 21, as that will result in a bust, and you'll lose the game.

5. The dealer (computer) will not draw any cards in this version of the game. Your goal is to try and get a higher hand value than the dealer without going over 21.

## Game Controls

- **Start Game:** Click the "Start Game" button to begin the game. This will deal you two cards to start.

- **Draw a New Card:** Click the "Draw a New Card" button to request a new card and add it to your hand. This option is only available if you have not reached 21 or busted.

## Player Information

At the beginning of the game, you are assigned the name "Per" and given 200 chips to play with. Your current chip count is displayed in the top-right corner as "Player Name: $X", where X is the number of chips you have left.

## Code Structure

The game code is written in JavaScript and is structured as follows:

- `player`: An object representing the player's name and chip count.

- `cards`: An array to hold the current cards in the player's hand.

- `sum`: A variable to keep track of the total sum of the player's hand.

- `hasBlackJack`: A boolean variable to check if the player has Blackjack (a total of 21).

- `isAlive`: A boolean variable to check if the player is still in the game.

- `message`: A variable to store messages about the game's current state.

- `getRandomCard()`: A function to generate a random card value between 1 and 11.

- `startGame()`: A function to start the game by dealing two cards to the player and calculating the initial sum.

- `renderGame()`: A function to update the game interface based on the current game state.

- `newCard()`: A function to draw a new card and update the game state.

## Have Fun!

Enjoy playing Blackjack! Test your luck and see if you can beat the dealer. Good luck and have fun! If you have any questions or feedback, feel free to contact us.

Best regards,
Sheeraz Ahmed
