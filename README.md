# Sanke-game..
The Classic Snake Game in Python was made using OOP and the turtle module.

The Classic Snake Game implemented in Python using Object-Oriented Programming (OOP) and the turtle module provides a graphical interface and game logic. This approach leverages the turtle module for drawing the game elements like the snake and food, and OOP principles to structure the code into reusable components.

Key Components and Concepts:
turtle Module:
Used to create the game window and draw the snake segments, food, and score display.
Provides functions for moving the "turtle" (representing the game elements), changing its shape and colour, and handling screen updates.
Object-Oriented Programming (OOP):
Classes: Typically, separate courses are created for the Snake and Food objects.

Snake Class:
Manages the snake's body segments (often turtle objects themselves).
Handles movement logic (changing direction, moving segments).
Includes methods for growing the snake when food is eaten.
Manages collision detection with walls or its own body.
Food Class:
Represents the food item the snake consumes.
Randomly positions itself on the screen after being eaten.
Inheritance: Both Snake and Food classes can inherit from the turtle.Turtle class to gain access to its graphical capabilities.

Game Logic:
Game Loop: Continuously updates the game state, moves the snake, checks for collisions, and refreshes the display.
User Input: Keyboard listeners are used to detect arrow key presses and change the snake's direction.
Score Tracking: A score is maintained and displayed, often using another turtle object.
Game Over Conditions: The game ends when the snake collides with the boundaries or its own body.
Game Restart: Functionality to reset the game after a game-over event.
