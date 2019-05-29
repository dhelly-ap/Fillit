# Fillit
Fillit it’s a programm that will take a file as parameter, which contains a list of Tetriminos, and arrange them in order to create the smallest square possible with backtracking algorithm.

# Compile
Use make to compile. The executable name will be fillit.

# Usage
./fillit [file]

# Valid test file
 • Precisely 4 lines of 4 characters, each followed by a new line (well... a 4x4 square).
 
 • A Tetrimino is a classic piece of Tetris composed of 4 blocks.
 
 • Each character must be either a block character(’#’ ) or an empty character (’.’).
 
 • Each block of a Tetrimino must touch at least one other block on any of his 4 sides (up, down, left and right).

# For example:
....
####
....
....

...#
..##
...#
