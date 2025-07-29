# Herexen

by TDRR (C) 2025 (yes I'm just using the one template doomtools creates)

## What This Is

A (fully vanilla Doom-compatible) Heretic + Hexen crossover project, putting lots of weapons and monsters from those games (and some customs) into Doom. Some creative liberties were taken due to limitations.


## To Build This Project


This project requires the [DoomTools](https://github.com/MTrop/DoomTools) toolchain for
building it. Clone this project to a new folder and type:

	doommake init


...In order to ensure everything has been prepped correctly (some directories or files
may need extracting, downloading, or copying).

To clean the build folder, type:

	doommake clean


To both initialize and build this project and its distributable archive:

	doommake


To build the DeHackEd patch from DECOHack source:

	doommake patch


To convert raw assets to Doom assets:

	doommake convert


To build the assets WAD:

	doommake assets


To run this project (after setting the correct properties):

	doommake run


To build all components:

	doommake all


To build the full release:

	doommake release

