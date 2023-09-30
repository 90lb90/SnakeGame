# SnakeGame
Description
This project represents an implementation of the "Snake" game in the Java programming language. The game is created using the Java Swing library and consists of several classes, each of which performs specific functions in the game.

Project Structure
The project consists of the following classes:
1. Room
Room represents the game field and manages the game process.
It contains information about the width, height of the game field, the snake, and the mouse.
The main method run() starts the game loop and handles user keyboard input.
The print() method displays the current state of the game on the screen.
The eatMouse() and createMouse() methods control the appearance of a new mouse and its consumption.
sleep() introduces a pause between snake moves, which increases with the snake's length.
2. KeyboardObserver
KeyboardObserver monitors keyboard events and adds pressed keys to a queue.
It creates an invisible window to be able to track key events in the background.
3. Mouse
Mouse represents a class for tracking the mouse's position on the game field.
4. Snake
Snake represents the snake and controls its movement.
It contains information about the snake's movement direction, its state (alive or not), and a list of snake segments.
The move() method moves the snake one step based on the current direction.
The checkBorders() and checkBody() methods check whether the snake is within the game field and whether it intersects itself.
5. SnakeSection
SnakeSection represents an individual segment of the snake, defined by x and y coordinates.

Running the Game
The game is launched from the main method in the Room class. It creates an instance of the game, sets the initial movement direction of the snake, creates the first mouse, and starts the main game loop.

Game Controls
The game is controlled using arrow keys. Pressing the left, right, up, and down keys changes the snake's movement direction. Pressing the 'q' key quits the game.

Ending the Game
The game ends when the snake dies. A "Game Over!" message appears.

Important
This code represents a basic implementation of the "Snake" game and can be further enhanced and optimized to add new features and improve performance.
