# CSE210_Final_Project_Asteroid

# For the asteroid game works well it needs of import the following library:
import arcade
import math
import random
import os
from typing import cast

# To start the game run the command
python3 AsteroidsV3.py

# To facilitate the Maintenance I created some global variables that allow changing some configurations of the game without the necessity of changing the code.
SCREEN_WIDTH = 800
SCREEN_HEIGHT = 600
STARTING_ASTEROID_COUNT = 3
SCALE = 0.5
OFFSCREEN_SPACE = 300
LEFT_LIMIT = -OFFSCREEN_SPACE
RIGHT_LIMIT = SCREEN_WIDTH + OFFSCREEN_SPACE
BOTTOM_LIMIT = -OFFSCREEN_SPACE
TOP_LIMIT = SCREEN_HEIGHT + OFFSCREEN_SPACE
TITLE= " <---- *** A S T E R R O I D S *** ----> "
