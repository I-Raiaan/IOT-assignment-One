# Dodge the Obstacles

Dodge the Obstacles is a game created using the Microbit Python Editor. The objective of the game is to avoid obstacles as they fall from the top of the LED matrix. 

## How to Play

The player can move left or right using buttons A or B, respectively. The game starts with three lives, and the player loses one life each time they collide with an obstacle. The game ends when the player has no lives remaining, and their final score is displayed. 

## How it Works

The game works by creating a list of obstacles at random x-coordinates along the top row of the LED matrix. The obstacles are then moved down by one row every loop iteration. The player's position is updated when buttons A or B are pressed, and their position is checked against the obstacles to detect collisions. 

If a collision occurs, the player loses a life. If the player has no lives remaining, the game ends and the score is displayed. Otherwise, the remaining lives are displayed, and the game continues. 

The game loop runs indefinitely, and the speed of the game is controlled by the sleep() function at the end of the loop.

## Installation

To play the game, follow these steps:

1. Go to the Microbit Python Editor website (https://python.microbit.org/v/2.0).
2. Create a new project and copy and paste the code from this repository into the editor.
3. Save the code to your Microbit device.
4. Press the reset button on your Microbit to start the game.

## Credits

This game was created by Ibrahim Raiaan for a project at UWE University. 
