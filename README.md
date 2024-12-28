![image](https://github.com/user-attachments/assets/63b5eea2-f1b7-4fb9-a850-aed2fe520e3b)

# Memory Card Game

This is a simple and fun **Memory Card Game** built using HTML, CSS, and JavaScript. The game includes two versions: one with a timer and one without. The objective of the game is to match all pairs of cards by flipping them over. In the version with the timer, players must complete the game before the time runs out, adding an element of challenge.

The game is designed to be **responsive**, ensuring that it can be played on various screen sizes, including desktops, tablets, and smartphones.

## Table of Contents
- [Project Structure](#project-structure)
- [How to Play](#how-to-play)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation Instructions](#installation-instructions)
- [Responsive Design](#responsive-design)
- [License](#license)

---

## Project Structure

This project consists of two demos, each contained within separate folders. Both versions contain HTML, CSS, and JavaScript files, along with image assets for the cards.

```
Memory-Card-Game/
│
├── Demo 1/
│   ├── images/           # Image assets for the cards (Demo 1)
│   ├── index.html        # HTML file for the demo without timer
│   ├── script.js         # JavaScript for the demo without timer
│   └── style.css         # CSS for styling the demo without timer
│
├── Demo 2/
│   ├── images/           # Image assets for the cards (Demo 2)
│   ├── index.html        # HTML file for the demo with timer
│   ├── script.js         # JavaScript for the demo with timer
│   └── style.css         # CSS for styling the demo with timer
│
└── README.md             # This file
```

### Demo 1: Without Timer
In this version, the player has unlimited time to match pairs of cards. It's a more relaxed version of the game where players can take their time and focus on memory.

### Demo 2: With Timer
In this version, the player has a set time limit (usually displayed at the top) to match all the pairs. The timer increases the challenge, encouraging quicker decision-making.

---

## How to Play

### Objective:
The goal of the game is to match all pairs of cards by flipping them over. Each pair contains identical cards, and you need to find them all.

### Gameplay:
1. **Start the Game**: Open the `index.html` file from either **Demo 1** or **Demo 2** folder in a web browser.
2. **Flip Cards**: Click on a card to flip it over. Then, click another card to see if it matches the first card. If the cards match, they stay face-up; otherwise, they will be flipped back face-down.
3. **Winning**: The game ends when all pairs have been matched.
4. **Timer Version**: If you are playing **Demo 2** (with a timer), the clock will count down. You must match all cards before time runs out. A sound or visual cue will signal when time has expired.

---

## Features

- **Card Matching**: Flip two cards at a time to check if they match.
- **Timer Version**: Race against the clock in **Demo 2** to match all the pairs before time runs out.
- **Responsive Design**: The game is fully responsive, which means it automatically adjusts to different screen sizes, from large desktops to small mobile screens.
- **Simple Gameplay**: The rules are easy to understand and can be enjoyed by players of all ages.
- **Image Assets**: Cards are represented with images (e.g., animals, shapes, numbers), making the game visually appealing.

---

## Technologies Used

- **HTML**: The game’s structure and content.
- **CSS**: The styling and layout, including responsive design.
- **JavaScript**: The game logic, including flipping cards, checking for matches, and handling the timer functionality.
- **Responsive Design**: Media queries in CSS ensure that the game looks great on all devices, from desktops to smartphones.

---

## Installation Instructions

1. **Download or Clone the Repository**:
   - To download, you can click the **Download ZIP** button on GitHub, or
   - To clone, use the following Git command:
   ```bash
   git clone https://github.com/GZ30eee/memory-card-game.git
   ```

2. **Navigate to the Demo Folder**:
   - Inside the project folder, go to either `Demo 1` or `Demo 2` depending on which version you want to play.

3. **Open the Game**:
   - Open the `index.html` file in any modern web browser (e.g., Chrome, Firefox, Safari).

4. **Play the Game**:
   - Enjoy the game by matching pairs of cards. If you are using **Demo 2**, try to finish before the timer runs out!

---

## Responsive Design

This game has been designed to be fully responsive. Whether you're on a large desktop, a tablet, or a mobile phone, the layout and functionality will adapt to the screen size.

### Mobile-Friendly Features:
- **Auto Resizing Cards**: The card size adjusts dynamically based on the screen size, making it easier to interact with them on smaller screens.
- **Stacked Layout**: On mobile devices, the cards stack in a single column or adjust to a grid layout for optimal touch interaction.
- **Touch Support**: The game supports touch gestures, so players on mobile devices can tap on cards to flip them over.

### How the Responsiveness Works:
The CSS uses **media queries** to adjust the layout and design based on the screen width. For example:
```css
@media (max-width: 768px) {
  .game-board {
    grid-template-columns: repeat(4, 1fr); /* Cards arranged in 4 columns on smaller screens */
  }
}
```
As a result, the game looks great and is playable on various devices without any horizontal scrolling or layout issues.

---

## License

This project is open-source and available under the **MIT License**.
