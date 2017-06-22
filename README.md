# mini-rogue-python
This is a python implementation of the Print-n-play game Mini Rogue. 

All copyrights, credits, and game can be viewed and downloaded here: http://mountaingoldgames.com/index.php/2016/05/06/mini-rogue-print-and-play-is-out-now/

I strongly recommend reading the rules from the actual game and visualize the cards before playing, this is just an easy way to play on the terminal.

It does have input limitations. For example, inputting anything else in a [y/n] question will make the game crash. The good news is that at every new Area you enter, the game automatically saves and you can reload it when you start again.

By the end of game (if you die or win) a plot of your dice roll distribution will be plotted, and after closing it you can input your name into a local Leaderboard divided by difficulty level.

## How to run it?
Just copy the repository to any folder, cd into it, and type `python mini_rogue.py` if you have python 3+ or `python mini_rogue_py2.py` if you have python 2 installed.

Required libraries are:
numpy
pandas
matplotlib

Hope you have fun!
