# Kung Fu Panda Memory Game by NicoCT04

## Description

This project is a memory game inspired by *Kung Fu Panda*. The goal of the game is to match all the cards in the fewest moves possible. The game is developed in **React** and uses a single HTML file with Babel to compile JSX directly in the browser.

---

## Features

- **4x4 card grid:** The cards are organized in a 4x4 grid.
- **Randomized cards:** The cards are shuffled randomly every time the game starts or restarts.
- **Flip animation:** The cards have a smooth flip animation.
- **Move counter:** Displays the number of moves made by the player.
- **Victory message:** A message appears when the player matches all the cards.
- **"Play Again" button:** Allows restarting the game with a new shuffle of cards.
- **"Return to Menu" button:** Allows returning to the main menu.
- **GitHub button:** Link to the project's repository.

---

## Technologies Used

- **React:** For creating components and managing state.
- **Babel:** To compile JSX directly in the browser.
- **HTML and CSS:** For the structure and design of the game.

---

## Project Structure

The project is contained in a single HTML file that includes:

1. **CSS Styles:** For the game's design, animations, and buttons.
2. **React Components:**
   - `App`: Main component that controls whether the menu or the game is displayed.
   - `Menu`: Main menu component with buttons to start the game and access the GitHub repository.
   - `Game`: Game component that includes the card logic, move counter, and victory message.

---

## How to Play

1. **Start:**
   - When the page loads, the main menu is displayed with the game's title and two buttons:
     - **Begin:** Starts the game.
     - **GitHub:** Opens the project's repository in a new tab.

2. **Game:**
   - Click on the cards to flip them.
   - If the two selected cards match, they remain flipped.
   - If they do not match, they flip back after 1 second.
   - The goal is to match all the cards in the fewest moves possible.

3. **Victory:**
   - When all the cards are matched, a victory message appears with a button to restart the game.

4. **Options:**
   - **Play Again:** Shuffles the cards and restarts the game.
   - **Return to Menu:** Returns to the main menu.


---

## Repository Link

You can find the project's source code at the following link:

[Kung Fu Panda Memory Game - GitHub](https://github.com/nicoCT04/Kungfu-memory.git)

---



## Future Improvements

- Add difficulty levels with different grid sizes (e.g., 6x6 or 8x8).
- Implement a timer to measure the time taken to complete the game.
- Save the highest score in the browser's local storage.
- Add sound effects when flipping cards or winning the game.

---

Thank you for playing! 😊
