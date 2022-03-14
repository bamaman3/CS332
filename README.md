# CS-332: Lab-1

## Purpose:
Add functionality to the search program iplmemented in project 2 to support unix commands

## How to Compile:
gcc hw3.c -o hw3

## How to Execute:
./hw3 <Path> [flags]'
    flags may be:
        1. -S (prints size of each file)
        2. -s <size> (prints only files greater than or equal to size)
        3. -f <string pattern> (prints only files whose file or directory name contains the substring)
        4. -e "args"


## Author(s)
Michael Moran

## Credits:
1. This program is based on my HW2 submission, and is mostly reused code.
    -As such, all applicable credits from HW2 also apply here.
2. Canvas resources (hw3.pdf, lecture slides, lab 8 recording, etc.) were used to better understand the assignment and applicable functions.
3. Refresher on exec: https://www.youtube.com/watch?v=OVFEWSP7n8c&ab_channel=CodeVault  
4. 