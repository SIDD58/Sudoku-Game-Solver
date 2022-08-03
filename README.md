
# Sudoku Solver Game 

[![MIT License](https://img.shields.io/apm/l/atomic-design-ui.svg?)](https://github.com/tterb/atomic-design-ui/blob/master/LICENSEs)


## Introduction

It is a Sudoku Solver Game made in python. You can solve the 
puzzle on your own and if you get stuck , Backtracking algorithm 
will solve the whole puzzle.

## Demo

**Inputting Values in the cells**
<p><img  align="left" src="https://github.com/SIDD58/Sudoku-Game-Solver/blob/main/assets/input.gif" alt="front-image" width="500" height="500"></img></p>

**Backtracking Solving the Puzzle Visually**
<p><img align="right"src="https://github.com/SIDD58/Sudoku-Game-Solver/blob/main/assets/solver.gif" alt="front-image" width="500" height="500"></img></p>

## Requirements

The Project was made using python 3.9.13 and 
pygame 2.1.2 . Only requiremtnt is to install python 3.0+
and pygame module using pip .

## User Manual
First Click on the cell , Where you want to insert a value

| Key | Function|
| :-------- | :------------------------- |
| `1-9 numpad keys` | You can enter only these value |
| `Enter Key` |Use When you are sure to confirm your entry |
| `Delete Key` |Use to delete the entry |
| `Space bar` | Use when you want backtracking to solve entire puzzle |

## Explanation

**Backtracking Algorithm**: It is a recursive algorithm . It
iterates over the available options , it first tries to 
build solution from first option , if at some stage 
contraints are not satisfied it backtracks to try another 
option and do this repeatedly in a recursive way untill
it finds the solution.
**How it works**:</br>1) First user should click on the cell
where he wants to put the entry (0-9) , and enter the 
numeric value.  
2) If the user sure of the entry then he should press enter 
key else if he thinks he has to go another cell , he can 
either levae cell as it is or delete the cell value using
delete key <br />
3) If user is stuck at some point then he can press space bar 
and backtracking algorithm will run visually to solve the 
puzzle <br />


## Authors

- [@SIDD58](https://github.com/SIDD58)


