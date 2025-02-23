[Game Demo Video](https://youtu.be/hDnoJq8jv1k)\
Author: Yunyu Yang
## The goals of the game 
The goal of the game is to control the bee as it flies across the spiders and their lair to achieve a high score. The game ends when the flying bee touches any spider, the spider lair, or hits the ground.
Elements of the game 
## Player:
- The lazy bee serves as the player. Three pictures are used to animate the flying bee, and these images are my original creations.
Obstacles: 
- Spiders: The upper layer of obstacles, which are my original designs.
- Spider Lair: The middle layer of obstacles, which is also my original design.
- Ground: An uneven ground image forms the bottom layer of obstacles, which is my original creation.
## The UI:
- Start button:  Displays at the beginning of the game, allowing the player to start the game by clicking it.
- Exit button: Displays at the beginning of the game, allowing the player to exit the game by clicking it.
- Game Over:  An image displayed when the game is over.
- Instructions: A brief guide explaining how to play the game.
## Environment:
- 	Background: An image of a cave sourced from online resources.

## How the elements moved
The bee moves upward when the space key is pressed or when the left mouse button is clicked. Gravity is applied to the bee, so the player must fly against gravity while avoiding spiders.
How the elements interact
- When the start button is pressed, the game begins, and all the spiders and the spider lair start moving toward the player. The game’s theme music begins to play, and the score starts at zero.
- Each time the bee flies, the "operation" sound effect is played.
- The score increases by one each time the bee passes through an obstacle, accompanied by the "gain_score" sound effect.
- All obstacles have colliders for trigger detection. When the bee collides with any of the obstacles, the "game_over" image, instructions, and start button are displayed. The "game_over" sound effect is played, and the theme music stops.
- When click the exit button, the game closes.
