# battleship
Battleship Board Game Using Curses in Python

This is a Python-based project inspired by the classic board game Battleship. You can read more about the original game here: https://en.wikipedia.org/wiki/Battleship_(game).

In this project, I've used the curses library to create a graphical user interface (GUI) within a text-based environment. The curses library allows for creating text-based user interfaces in such environments. You can learn more about curses here: https://docs.python.org/3/howto/curses.html.

I've implemented the game using Object-Oriented Programming (OOP), with three main classes: Player, Coordinate, and Ship.

Additionally, I've incorporated the argparse module to handle command-line arguments, allowing users to specify the number of rows and columns for the game board. For example, you can start the game with a 5x5 grid by running the following command:

python battleship.py 5 5
