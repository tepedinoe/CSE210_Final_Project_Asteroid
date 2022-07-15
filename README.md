# CSE210_Final_Project_Asteroid

# For the asteroid game works well it needs of import the following library:
import arcade <br>
import math <br>
import random <br>
import os <br>
from typing import cast <br> <br>

# Description
To start the game run the command <br>
python3 AsteroidsV3.py <br>
When you start the game his purpose is to maneuver the spaceship and dodge the asteroids and shoot and destroy the asteroids.
To shoot use the tab key and to dodge the asteroids and maneuver spaceship use the arrow keys.
<br>
<br>
 Classes structure
I used the following classes:
1) class TurningSprite(arcade.Sprite) that sets its angle to the direction in the spaceship is traveling in. It derives from an arcade. Sprite.
2) class ShipSprite(arcade.Sprite): It represents our spaceship that Derives from arcade. Sprite.
3)  class AsteroidSprite(arcade.Sprite): It represents the Asteroids of all sices and moving. It derives from an arcade. Sprite.
4) class Game(arcade.Window): Main application class.  It is responsible for spacecraft controls and pulling images of spacecraft and meteors. It is responsible for the movement of meteors. It is also responsible for recording scores.
To start the game I did the main function to be responsible to start the game.
<br>
To facilitate the Maintenance I created some global variables that allow changing some configurations of the game without the necessity of changing the code. <br>
SCREEN_WIDTH = 800 <br>
SCREEN_HEIGHT = 600 <br>
STARTING_ASTEROID_COUNT = 3 <br>
SCALE = 0.5 <br>
OFFSCREEN_SPACE = 300 <br>
LEFT_LIMIT = -OFFSCREEN_SPACE <br>
RIGHT_LIMIT = SCREEN_WIDTH + OFFSCREEN_SPACE <br>
BOTTOM_LIMIT = -OFFSCREEN_SPACE <br>
TOP_LIMIT = SCREEN_HEIGHT + OFFSCREEN_SPACE <br>
TITLE= " <---- *** A S T E R R O I D S *** ----> " <br>

