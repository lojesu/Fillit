# Fillit
# Introduction
Introduction to the algorithmic program, in particular with the concept of "Backtracking", this project consists of arranging tetrimos (form of the tetris game) given in the smallest possible square
# Get started
## Launch
Use: ```git clone https://github.com/lojesu/Fillit.git ; cd Fillit; make; make clean```
## Run with a map
./fillit <map's path>
# How create a map ?
In a file create some tetriminos, every tetriminos must be seperate with one empty line

The description of a Tetriminos must respect the following rules:
- Exactly 4 lines of 4 characters followed by a line break. 
- A Tetriminos is a classic Tetris piece made up of 4 blocks. 
- Each character must be either a '#' when the box corresponds to one of the 4 blocks of a Tetriminos, ie a '.' when the box is empty 
- Each block of a Tetriminos must be in contact with at least one other block on one or the other of its 4 sides.

Some examples of valid Tetriminos descriptions:

![https://github.com/lojesu/Fillit/blob/master/screenshot/valids.png](https://github.com/lojesu/Fillit/blob/master/screenshot/valids.png)

Some examples of invalid Tetriminos descriptions:

![https://github.com/lojesu/Fillit/blob/master/screenshot/invalids.png](https://github.com/lojesu/Fillit/blob/master/screenshot/invalids.png)

# solution result
the goal being to achieve the smallest possible square with all the tetriminos, we will distinguish the tetriminos with capital letters like this:

![https://github.com/lojesu/Fillit/blob/master/screenshot/result.png](https://github.com/lojesu/Fillit/blob/master/screenshot/result.png)

# Contributos
- Lojesu
