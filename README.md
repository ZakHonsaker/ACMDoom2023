# [ACM Doom 2023]

by the University of Dayton chapter of the Association for Computing Machinery

## About

This is just something we decided to do for fun. A little exercise in computer science, if you will.

Some directories/files in this project are ignored (or *should* be ignored) by repository "ignore" files:

	/build               Build directory.
	/dist                Distributables directory.
	doommake.properties  Project property override file.


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


To convert raw assets to Doom assets:

	doommake convert


To build the assets WAD:

	doommake assets


To convert raw texture assets to Doom assets:

	doommake converttextures


To build the texture resources:

	doommake textures


To build just the maps WAD:

	doommake maps


To extract only the textures used by maps to a separate WAD file (if any):

	doommake maptextures


To build all components:

	doommake all


To build the full release:

	doommake release

