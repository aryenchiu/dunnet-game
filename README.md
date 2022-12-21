# Dunnet Game
## Introduction
* To play with the original [dunnet game](https://en.wikipedia.org/wiki/Dunnet_(video_game)) in emacs, just type the command below.
```shell=
emacs -batch -l dunnet
```
* This program simulates the dunnet game by only using C shell script to manipulate some file structure.
* It only tested properly under Ubuntu Linux, we could not assure whether it could be executed under other UNIX-based systems.

## Procedure to execute
* To execute the program, change your current directory to root and clone the repo first.
```shell=
git clone https://github.com/aryenchiu/dunnet-game.git
```
* Then change your shell into tcsh.
```shell=
tcsh
```
* Finally, execute the program by typing the command below.
```shell=
source ./dunnet-game/PA4assignment/PA4prog.csh
```

## Commands in the game

```
Directions:

e	 :	East
w	 :	West
n	 :	North
s	 :	South
u	 :	Up
d	 :	Down
ne	 :	Northeast
nw	 :	Northwest
se	 :	Southeast
sw       :	Southwest

Other commands:

i        :      inventory (to check what you have in your inventory)
l        :      list (the description of where you at)
```
