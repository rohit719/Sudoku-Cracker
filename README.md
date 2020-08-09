# Sudoku-Cracker

Sudoku cracker is a soduko solver app which uses Backtracking Algorithm to solve the sudoku puzzle.
This project has 2 versions :  Interactive GUI game version & Text based version.

## Rules to solve sudoku puzzle:
   
   Sudoku is played on a grid of 9 x 9 spaces. Within the rows and columns are 9 “squares” (made up of 3 x 3 spaces). 
   Each row, column and square (9 spaces each) needs to be filled out with the numbers 1-9, without repeating any numbers within the row, column or square.

## Approach followed to solve the puzzle(ALGORITHM):
   
   1) Pick an empty box
   2) Try all numbers from 1-9 in the empty box
   3) Select one number that satisfy the puzzle's rule and allot the empty space to the selected number.
   4) Repeat the above procedure for the next empty boxes.
   5) When the board reaches a state from where the puzzle can't be solved, backtrack to the previous correct solvable state of the board.
   6) Try other valid numbers in the empty boxes.
   7) Repeat the above steps till eventually correct solution is obtained.
   
## Instruction to play the GUI game version:
   1) Click a box and hit the number on your keyboard to pencil in a number.
   2) To confirm that value press the ENTER key on that box. 
   3) To delete a pencil in you can click DEL. 
   4) Finally to solve the board press SPACE, sit back and watch the algorithm run.


### The working of Backtracking Algorithm can be visualized while solving the board.
