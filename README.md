# Overview
Greed is a game in which the player seeks to gather as many falling gems as possible. The game continues as long as the player wants more!

## Getting Started
---
Make sure you have Python 3.8.0 or newer and Raylib Python CFFI 3.7 installed and running on your machine. You can install Raylib Python CFFI by opening a terminal and running the following command.
```
python3 -m pip install raylib
```

# Rules
Greed is played according to the following rules.

Gems (*) and rocks (o) randomly appear and fall from the top of the screen.
The player (#) can move left or right along the bottom of the screen.
If the player touches a gem they earn a point.
If the player touches a rock they lose a point.
Gems and rocks are removed when the player touches them.
The game continues until the player closes the window.

## Project Structure
---
The project files and folders are organized as follows:
```
root                    (project root folder)
+-- greed                 (source code for game)
  +-- game              (specific game classes)
  +-- __main__.py       (entry point for program)
+-- README.md           (general info)
```

## Required Technologies
---
* Python 3.8.0
* Raylib Python CFFI 3.7

## Authors
---
* Jeremiah Joseph Miclat (jeremiah_miclat@byui.edu)
