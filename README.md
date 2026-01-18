# GAME-DEVELOPMENT-SNAKE-GAME-CODTECH_IT

*COMPANY *: CODTECH IT SOLUTIONS

NAME: DHATSHINI A

INTERN ID: CTIS2275

DOMAIN: C++ PROGRAMMING

DURATION: 4 WEEEKS

MENTOR: NEELA SANTHOSH

# DESCRIPTION

The Snake Game is a classic console-based game developed using C++ that demonstrates fundamental concepts of game development, real-time input handling, and logical state management. This project recreates the traditional snake gameplay experience within a text-based console environment, providing an interactive and engaging way to understand core programming principles.

The game operates within a fixed two-dimensional grid defined by a width and height of 20 units each. The playing area is visually represented using characters, where the snake’s head, tail segments, boundaries, and fruit are rendered dynamically on the console. The snake’s head is represented by the character O, the tail by o, and the fruit by @. The game boundaries are drawn using underscores and vertical bars to clearly define the playable area.

The program is structured into multiple well-defined functions to maintain clarity and modularity. The Setup() function initializes all essential game variables, including the snake’s starting position, the initial direction, fruit placement, score, and game state. Random positioning of the fruit ensures unpredictability and replayability.

The Draw() function is responsible for rendering the game screen. It clears the console and redraws the entire grid during each iteration of the game loop. This includes the snake’s current position, its growing tail, the fruit, and the score display. By continuously updating the visual output, the game creates the illusion of motion within a text-based interface.

User input is handled in real time using the Input() function. The program utilizes non-blocking keyboard input methods to capture player commands without interrupting the game flow. The player controls the snake’s movement using the W, A, S, and D keys, allowing movement in four directions—up, left, down, and right. An additional key allows the player to exit the game at any time. This real-time responsiveness is a key aspect of interactive game design.

The core game mechanics are implemented in the Logic() function. This function updates the snake’s position based on user input, manages tail movement, detects collisions, and handles scoring. When the snake consumes a fruit, its length increases, and the score is incremented. Collision detection ensures that the game ends if the snake runs into its own tail. Boundary logic allows the snake to wrap around the screen edges, maintaining continuous gameplay.

The main game loop runs continuously until a game-over condition is met. The loop repeatedly calls the drawing, input, and logic functions while controlling the game speed using a delay mechanism. This ensures smooth gameplay and consistent motion across systems.

Overall, this Snake Game project effectively demonstrates essential concepts such as game loops, real-time input handling, array-based data structures, conditional logic, and state management in C++. It serves as a strong introductory project for understanding the fundamentals of game development and interactive programming in a low-level environment.


# OUTPUT 

<img width="254" height="532" alt="Image" src="https://github.com/user-attachments/assets/a9f6c292-3554-4893-9437-57932c027695" />
