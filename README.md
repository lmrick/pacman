# Pac-Man Game in Java (Swing)

A classic Pac-Man-style 2D game developed using pure Java with Swing and AWT. This project was built for learning purposes, focusing on object-oriented programming, game loop architecture, and graphical rendering without the use of external game engines.

# Features

- 2D grid-based maze system (tilemap)
- Player-controlled Pac-Man with keyboard input
- Enemy ghosts with basic AI (random movement logic)
- Collision detection system
- Score and lives system
- Animated rendering using Java Swing (Graphics2D)
- Game loop implemented with `javax.swing.Timer`
- Level progression with increasing difficulty

# Technologies Used

- Java 8+
- Java Swing (GUI)
- AWT (Graphics & Events)
- Object-Oriented Programming (OOP)

# How to Run

## Requirements

- Java JDK 8 or higher

## Steps

```bash
# Clone the repository
git clone https://github.com/lmrick/pacman.git

# Navigate to the project folder
cd pacman

# Compile the project
mvn package fun/pacman/*.java

# Run the game
java fun.pacman.Pacman
```

# Controls

⬅️ Move Left  
➡️ Move Right  
⬆️ Move Up  
⬇️ Move Down  
SPACE → Start Game  
ESC → Exit Game  

# Game Mechanics

Pac-Man moves on a grid-based system aligned with the tile map.

Ghosts use randomized movement logic when reaching intersections.

Collect dots to increase score and clear the level.

Avoid ghosts — collision reduces lives.

Completing a level increases difficulty (more ghosts and speed).

# Learning Goals

This project was built to practice and understand:

Object-Oriented Programming (OOP) in Java  
Game loop architecture  
Event-driven programming  
2D rendering using Java Swing/AWT  
Basic AI behavior for enemies  
Grid-based map systems  

# Future Improvements

Smarter ghost AI (pathfinding)  
Sound effects and background music  
Multiple levels with external map loading  
Pause menu and restart system  
High score persistence  

# Author

Developed by @lmrick  
For learning and portfolio purposes.

# License

This project is open-source and free to use for educational purposes.

# Screenshots

![Gameplay Screenshot 1](https://user-images.githubusercontent.com/110359490/220905118-625b3bb1-8be0-4407-8a0d-5253968d3c7e.png)

![Gameplay Screenshot 2](https://user-images.githubusercontent.com/110359490/220905179-efa639c5-d0b9-4d2d-a0d9-fda19b832514.png)
