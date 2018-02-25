# Stacker
Stacker is an arcade game where the goal is to build a stack of blocks as high as possible.

<p align="center">
  <img src="https://user-images.githubusercontent.com/9711999/36637638-918c67a6-1a34-11e8-8550-f69a5e724759.gif" alt="Stacker game" />
</p>

At each level, a row of blocks moves sideways and the user has to lock the blocks in place (using the SPACE key) and timing it so that it aligns with the previous level. Blocks that don't align are lost and if no blocks aligned at all, the player loses.

As the levels increase, the blocks move faster making timing even more critical.

This program was written in the Jack language for [project 9](http://nand2tetris.org/09.php) in the [nand2tetris](http://nand2tetris.org/) course.

## Install
Download the software suite from [nand2tetris](http://nand2tetris.org/software.php). The compiler and emulator are required as Jack programs run on the Hack hardware platform.

## Build & Execution
1. In the command line run:
```
JackCompiler.bat
VMEmulator.bat
```
replacing `.bat` with `.sh` for Mac/Linux

2. In the menu, goto `File > Load Program` and choose the directory containing the vm files.
2. Click yes in the confirmationg dialog
2. In the toolbar, choose `No animation` in the `Animate` dropdown
2. In the toolbar, click the double right arrows (3rd icon)
2. Play the game!
