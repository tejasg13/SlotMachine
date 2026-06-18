# SlotMachine
# 🎰 Slot Machine Game

## Game Overview

Slot Machine is a casino-style game developed in Unity using C#. Players start with a set number of coins, place bets, and spin three reels containing different symbols. If all three reels stop on the same symbol, the player wins coins based on their bet amount. The game includes sound effects, animations, floating win messages, and a coin management system to create an engaging gameplay experience.

---

## Instructions to Run WebGL Build

1. Download or clone the project repository.
2. Open the **WebGL Build** folder.
3. Run the project using one of the following methods:

   * Upload the WebGL build to a web hosting service such as GitHub Pages, itch.io, or Netlify.
   * Use a local web server to host the build files.
4. Open the generated URL in a modern web browser (Chrome, Firefox, Edge, etc.).
5. Click **Play** and start spinning the reels.

---

## Bonus Features

* Coin and betting system
* Floating text notifications for wins
* Sound effects for spinning and winning
* UI for displaying current coin balance
* Randomized reel spinning animations
* Responsive gameplay suitable for WebGL deployment

---

## Thought Process / Approach

The goal of this project was to create a simple yet enjoyable slot machine experience while practicing Unity game development concepts. The project was divided into several components:

1. Reel System

   * Created individual reels that randomly stop on different symbols.
   * Ensured each reel spins independently before stopping.

2. Game Logic

   * Implemented betting and coin management.
   * Added win detection by comparing the final symbols of all reels.

3. User Interface

   * Designed a clean UI to display coins, bets, and game status.
   * Added floating text messages to provide feedback to the player.

4. Audio & Visual Feedback

   * Added sound effects for reel spinning and winning.
   * Included animations to make the game feel more interactive.

5. WebGL Optimization

    Tested the game in WebGL builds to ensure compatibility and smooth performance in browsers.

This project helped improve my understanding of Unity UI systems, game state management, coroutines, audio handling, and gameplay programming using C#.
