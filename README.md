# Beakout_50 

**Beakout_50** is a *Breakout*-style arcade game developed as part of the [Harvard CS50x](https://cs50.harvard.edu/x/) Introduction to Game Development course. Built using the **Lua** programming language and the **LÖVE2D** framework, this project showcases the fundamentals of 2D game development with classic arcade fun and modern code structure.

---


## Table of Contents

- [ About](#about)
- [Features](#features)
- [ Gameplay](#-gameplay)
- [ Features](#-features)
- [ Built With](#️-built-with)
- [ Controls](#-controls)
- [ How to Run](#-how-to-run)
- [ Project Structure](#-project-structure)
- [ Learning Highlights](#-learning-highlights)
- [ License](#-license)
- [ Acknowledgements](#-acknowledgements)

---

## About

This project is a faithful clone of _Breakout_, created for the CS50's GD50 course. Through this, I practiced concepts like game state management, collision detection, OOP in Lua, and asset management. This repository showcases my learning in game programming and serves as a foundation for creating more complex games in the future.

---

## Features

-  Classic brick-breaking gameplay
-  Smooth paddle and ball mechanics
-  Multiple brick layouts/levels
-  Score and lives tracking
-  Retro-inspired audio and visuals
-  Modular codebase using Lua and LÖVE2D


---

## Gameplay

Use the paddle to bounce the ball and break all the bricks on the screen. As the game progresses, new levels introduce more complex brick arrangements and faster gameplay. Catch falling power-ups and keep the ball from hitting the bottom of the screen!

---

## Features

-  Classic *Breakout* gameplay mechanics  
-  Smooth paddle and ball physics  
-  Power-ups and bonuses  
-  Sound effects and animations  
-  Score tracking and level progression  
-  Finite state machine for game states  
-  Modular object-oriented Lua code structure  

---

## Built With

- **Language**: Lua  
- **Framework**: [LÖVE2D](https://love2d.org/)  
- **Course**: [CS50's Introduction to Game Development](https://cs50.harvard.edu/games/)

---

## Controls

- `←` / `→`: Move paddle left/right  
- `Enter`: Start game / Advance to next screen  
- `Escape`: Exit the game  

---

## How to Run

**Requirements:**  
- [LÖVE2D](https://love2d.org/) (Love2D game framework installed)

**Steps:**

1. Clone this repository:
    ```
    git clone https://github.com/Viriviola/breakout-clone.git
    ```
2. Navigate to the project directory:
    ```
    cd breakout-clone
    ```
3. Launch the game:
    - **Drag the folder onto the LÖVE2D executable**, **or**
    - Run from terminal:
        ```
        love .
        ```

## How to Play

- **Move paddle:** Left and right arrow keys
- **Launch ball:** Space bar (if applicable)
- **Goal:** Break all bricks to complete the level
- **Lives:** Don’t let the ball fall below the paddle!

## Project Structure
```
breakout-50/
│
├── main.lua # Main entry point
├── src/ # Source code (game states, object control, etc.)
├── assets/ # Graphics, sounds, fonts
├── lib/ # classes
├── README.md # Project documentation
└── ... # Other files
```

## Learning Highlights
- By creating Beakout_50, I learned:
- Game loops and real-time input handling
- State management using finite state machines
- Physics for 2D collisions
- Sprite animation and sound integration
- Structuring games with object-oriented Lua
- Using LÖVE2D to build playable, polished games

## License
This project was created for educational purposes as part of the CS50 curriculum.
Feel free to use, modify, and learn from it with proper attribution.

## Acknowledgements
- Harvard CS50x
- CS50 Game Development Track
- LÖVE2D Game Framework
- The original Breakout game by Atari (1976)