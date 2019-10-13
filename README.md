# MIPS samegame

Assembly implementation of the game "samegame".

![Screenshot](https://upload.wikimedia.org/wikipedia/commons/4/4f/SameGame.jpg)

## Description

Samegame is a puzzle game released in 1985 in Japan by Kuniaki Moribe. The rules are very simple:

> SameGame is played on a rectangular field, typically initially filled with four or five kinds of blocks placed at random. By selecting a group of adjoining blocks of the same color, a player may remove them from the screen. Blocks that are no longer supported will fall down, and a column without any blocks will be trimmed away by other columns always sliding to one side (often the left). The goal of the game is to remove as many blocks from the playing field as possible.

_from [wikipedia](https://en.wikipedia.org/wiki/SameGame)_

As part of a school assignment of computer architecture class I had to implement this game in assembly. The target architecture was MIPS, a 32 bit processor with a reduced set of instructions (RISC).

## Setup

In order to execute the code you will need to install [MARS](http://courses.missouristate.edu/kenvollmar/mars/download.htm) on your machine, a MIPS that you can execute on all platforms with Java. MARS is an IDE that allows you to simulate and execute MIPS instructions. The only thing you need to do is to open the file __samegame.asm__ and to click on Run. Then just follow the instructions on the console and enjoy the game 😁
