*Pac-Man*
=======

A historical tribute and accurate remake of the original Pac-Man arcade game

Inspired by *The Pac-Man Dossier*

### Still Under Construction tho 😎


- [x] Sound
- [x] Cutscenes
- [x] Mars
- [ ] 2 Player switch-off


Contact me at [adeyinkazra123@gmail.com](mailto:adeyinkazra123@gmail.com)

License
-------

This program is free software: you can redistribute it and/or modify
it under the terms of the **GNU General Public License Version 3** as 
published by the Free Software Foundation.

Play
----

You can play the game on all canvas-enabled browsers.  **Touch controls** are
enabled for mobile browsers.  The game is **resolution-independent** and smoothly scales to
fit the size of any screen.  **Performance** may increase by shrinking the window or zooming in with your browser.

### Main Controls

- **swipe**: steer pacman on mobile browsers
- **arrows**: steer pacman
- **end**: pause the game
- **escape**: open in-game menu

### Confirmed Desktop Browers

- Microsoft Edge
- Firefox
- Chrome


Games
-----

Each of the following games are playable from the main menu.

![Montage](https://github.com/adeyinkaezra123/PacMan/blob/master/shots/montage.png)

- **Pac-Man**: 1980 original arcade by Namco.
- **Ms. Pac-Man**: 1981 Pac-Man modification by GCC/Midway.
- **Crazy Otto**: GCC's unreleased, in-house version of Ms. Pac-Man before it was sold to Midway. 
- **Cookie-Man**: a brand new version of Ms. Pac-Man with a sophisticated **procedural map generator**.

### Turbo Mode

Each game has an alternate mode called Turbo (a.k.a. *Speedy* mode).  This is a
popular hardware modification of the game found in many of the original arcade
cabinets.  In this mode, Pac-Man travels about twice as fast (same speed as the disembodied eyes of the
ghosts) and is not slowed down when eating pellets.

### High Scores

High scores for each game (normal and turbo separately) are stored on your local machine by your browser.

Learn Mode
----------

Learn Mode allows you to visualize the behaviors of the ghosts.  (The colored square represents the ghost bait.)

![Learn](https://github.com/adeyinkaezra123/PacMan/blob/master/shots/learn.png?raw=true)

Practice Mode
-------------

This mode allows you to practice the game with special features.  You can go
into **slow-motion** or **rewind time** with the special onscreen buttons or the hotkeys listed below.  (The time-manipulation controls and design were borrowed from the game [Braid](http://braid-game.com/)).  You can also turn on **invincibility** or **ghost visualizers** from the menu.

![Practice](https://github.com/adeyinkaezra123/PacMan/blob/master/shots/practice.png)

### Practice Controls

- **shift**: hold down to rewind (a la Braid)
- **1**: hold down to slow down the game to 0.5x
- **2**: hold down to slow down the game to 0.25x
- **o**: toggle pacman turbo mode
- **p**: toggle pacman attract mode (autoplay)
- **i**: toggle pacman invincibility
- **n**: go to next level
- **q,w,e,r,t**: toggle target graphic for blinky, pinky, inky, clyde, and pacman, respectively.
- **a,s,d,f,g**: toggle path graphic for blinky, pinky, inky, clyde, and pacman, respectively.

Procedurally-Generated Maps
---------------------------

In the **Cookie-Man** game mode, the mazes change as often as they do in Ms. Pac-Man, but are **procedurally generated**.  Each level has a pre-defined color palette, granting an element of consistency to the random structure of the mazes.

![Procedural](https://github.com/adeyinkaezra123/PacMan/blob/master/shots/procedural.png)

### Algorithm Description

The mazes are built carefully to closely match design patterns deduced from the original maps found in Pac-Man and Ms. Pac-Man.


### Report/Fix Bugs

Feel free to report any inaccuracies that may detract or simply annoy.  Any software engineers willing to contribute their expertise to this project would be a big help as well!

Navigating the Repository
-------------------------
- All javascript source files are located in the "src/" directory
- "index.html" displays the game by using the "pacman.js" file only
- the "fruit" directory contains notes and diagrams on Ms. Pac-Man fruit paths
- the "mapgen" directory contains notes, diagrams, and experiments on procedural Pac-Man maze generation
- the "sprites" directory contains references sprite sheets and an atlas viewer "atlas.htm" for viewing the scalable game sprites.
- the "font" directory contains font resources used in the game.

Credits
-------

### Original Games

Many Thanks to the original Pac-Man team at Namco for creating such wonnderful game.

