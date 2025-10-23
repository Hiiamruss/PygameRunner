# PygameRunner
It is a small windows program that enables you to run all sorts of Pygame Programs from games to other things.. really. (Supported file types .py)
@Hiiamruss
#Instructions

Games must follow a strict requirement to be able to run in PygameRunner.
1. They must include a class. 
2. The main class must be named Game()
3. The game loop must be named Loop()

How to install games?
1. Put your game files into the PygameRunner folder.
2. Open the addons.py in a text file.
3. Inside you will see this:

class Game:
    pass
games = None
#insert imports here! 
#example. from <game name> import Game
#For compatible games list, check readme.
4. Erase the comments "#" and replace them with this structure:
from <your game file name> import * (if you have multiple classes use "*", if you use multiple files, make them in the same folder as the program. 

Thanks for Downloading!
