# battleship
battleship board game using curses in Python

This is a game project in Python based on the classical board game of the same name. 
Read about it here - https://en.wikipedia.org/wiki/Battleship_(game)

I made this project using curses library in Python. Basically curses enables us to give the user a GUI inside the terminal.
Read more here - https://docs.python.org/3/howto/curses.html

I have used Object oriented programming to make this project. Player, Coordinate and Ship are the three classes in my project.

I have used argparse to parse the command line arguments so that the user can specify the number of rows and columns in the game as command line arguments like this-
python battleship.py <number of columns> <number of rows>
For example-
python battleship.py 5 5

Please note that this does not run properly inside VS Code integrated terminal, so you need to run it inside a stand alone termnial like the inbuilt terminals on Winodows and Linux.
