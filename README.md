Heart of the Alien 1.2.2 for BeOS
=================================

This is a BeOS port of Heart of Alien Redux - a recreation of Heart of the Alien game for modern PCs.
HotA was developed in 1994 as a sequel to one of the best adventure games - Another World.
Gil Megidish developed an open-source engine to play this game.

![Screenshot 1](/screenshot/hota-1.png?raw=true "Screenshot from BeOS")
![Screenshot 2](/screenshot/hota-2.png?raw=true "Screenshot from BeOS")
![Screenshot 3](/screenshot/hota-3.png?raw=true "Screenshot from BeOS")

#REQUIREMENTS

You need SDL libraries to run (or recompile) this game. Just go to src/ directory and use make.

Put 'rungame.sh' script and game binary 'alien' into directory with game data - ISO file and MP3 sounds.
(just unzip download from The Underdogs into the same directory).

#GAME

Just double-click on rungame.sh script and select some options. For more command line options, please
see documentation files from original release. The action keys are Z,X,C,Q,W,E, cursors and space.
You will get the idea...
On the startup press ESC to skip intro, then navigate to OK (unless you know passwords) and press Z.

#INFO

There were no BeOS specific changes to the code. The only thing I had to do was to cleanup
the sources somewhat and fix crash bug in decode.c when debug was disabled (that's the
new default).

#WARNING

You will die a thousand times in most unexpecting ways :).

#SOURCES

Game code:  http://hota.sourceforge.net/
SEGA CD game data: http://www.the-underdogs.info/game.php?id=3180
