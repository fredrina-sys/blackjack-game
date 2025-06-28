# 🃏 Blackjack Game

A web-based implementation of the classic Blackjack card game using **HTML**, **CSS**, and **JavaScript**. Challenge yourself by playing against the virtual dealer—try to hit 21 without going bust!

## 🎮 Gameplay Overview

- Draw two random cards to begin the game.
- Try to reach exactly 21 to win Blackjack.
- Go over 21 and you're out!
- Control your fate with the **New Card** button.
- Real-time UI updates for cards, sum, and game status.

## ⚙️ How It Works

- **getRandomCard()** simulates a real deck with face cards counting as 10 and aces as 11.
- **startGame()** initializes the game with two random cards and updates game state.
- **renderGame()** dynamically updates the UI with the card values, score, and game messages.
- **newCard()** lets the player draw another card—only if still alive and not already at Blackjack.

## 💡 Features

- Clean, responsive layout with visual card feedback
- Clear game rules and intuitive messaging
- Simple DOM manipulation and logic-driven UI flow
- Game state tracking using variables like `isAlive` and `hasBlackJack`

## 🛠️ Tech Stack

- **HTML** – Semantic structure
- **CSS** – Visual styling and layout
- **JavaScript** – Game logic and interactivity

## 🧪 Run It Yourself

1. Clone this repository:

   git clone https://github.com/fredrina-sys/blackjack-game.git
