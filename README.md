# fbtBlend-Header-Only


**fbtBlend** is a C++ .blend file parser from https://github.com/gamekit-developers/gamekit (available in the repository subfolder: /tree/master/Tools/FileTools).

Here there's a version updated to Blender 2.79 and amalgamated into two header files: **fbtBlend.h** and **Blender.h**.


## Demos

Two demos are available: **testConsole.cpp** and **testGlut.cpp** (they contain build instructions for Linux and Windows).

A third demo is present in the subfolder **test_skeletal_animation** (build instructions are at the top of **test_skeletal_animation/main.cpp**).

## Dependencies

* zlib (optional but recommended, to load compressed .blend files)

**testGlut.cpp and test_skeletal_animation need:**

* glut (or freeglut)
* glew (Windows only)

## Blender 2.80, 2.81 and 2.82 versions

In the *280*, *281* and *282* repository folders there are versions of **fbtBlend.h** and **Blender.h** updated for Blender 2.80, 2.81 and 2.82.
In the *280/tests*, *281/tests* and *282/tests* subfolders there are versions of **testConsole.cpp** and **testGlut.cpp** that should compile correctly with these versions.
Please note that **280/tests/testGlut.cpp**, **281/tests/testGlut.cpp** and **282/tests/testGlut.cpp** are the same as the 2.79 version, except that all materials have been stripped, because Blender>=2.80 doesn't support "Blender Internal" materials anymore.
Of course I'll **NEVER** make a version that can display physic-based materials... be warned!

## Screenshots
![testGlut](./screenshots/testGlut.png)

![test_skeletal_animation_header](./screenshots/test_skeletal_animation_header.png)
-------------------------------------------------------------------------------------
![test_skeletal_animation](./screenshots/test_skeletal_animation.gif)


## Useful Links:
[Gamekit Github Page](https://github.com/gamekit-developers/gamekit)





