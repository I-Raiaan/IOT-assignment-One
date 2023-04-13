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

1. Download the "dodge_the_obstacles.hex" file from this repository.
2. Connect your Microbit device to your computer using a USB cable.
3. Drag and drop the "dodge_the_obstacles.hex" file onto the Microbit device.
4. Disconnect the Microbit from your computer and press the reset button on your Microbit to start the game.

## Credits

This game was created by Ibrahim Raiaan for a project at UWE University. 
