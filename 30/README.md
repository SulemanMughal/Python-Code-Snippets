# Sudoku Solver

This is a script to solve a 9x9 sudoku matrix using Python.

#### How to use it?

-   edit **snippet-30.py** to add your **sudoku matrix**. (Fill 0 for empty cells.)

#### Example

-   Input Sudoku


        8 1 0 | 0 3 0 | 0 2 7
        0 6 2 | 0 5 0 | 0 9 0
        0 7 0 | 0 0 0 | 0 0 0
        ---------------------
        0 9 0 | 6 0 0 | 1 0 0
        1 0 0 | 0 2 0 | 0 0 4
        0 0 8 | 0 0 5 | 0 7 0
        ---------------------
        0 0 0 | 0 0 0 | 0 8 0
        0 2 0 | 0 1 0 | 7 5 0
        3 8 0 | 0 7 0 | 0 4 2


-   Output Sudoku


        8 1 4 | 6 3 9 | 5 2 7
        1 6 2 | 4 5 7 | 3 9 8
        1 7 2 | 4 3 5 | 6 9 8
        ---------------------
        2 9 3 | 6 4 5 | 1 7 8
        1 5 3 | 6 2 7 | 9 8 4
        1 2 8 | 3 4 5 | 9 7 6
        ---------------------
        1 2 3 | 4 5 6 | 7 8 9
        3 2 4 | 6 1 8 | 7 5 9
        3 8 5 | 6 7 9 | 1 4 2



