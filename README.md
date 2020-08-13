# Sudoku-solver-using-backtracking 
This is a program to solve sudoku using backtracking.Code was written in python.some GUI help was taken from online resources.
Algorithm:
1.Create a function that checks after assigning the current index the grid becomes unsafe or not. Keep Hashmap for a row, column and boxes. If any number has a frequency greater than 1 in the hashMap return false else return true; hashMap can be avoided by using loops.
2.Create a recursive function which takes a grid.
3.Check for any unassigned location. If present then assign a number from 1 to 9, check if assigning the number to current index makes the grid unsafe or not, if safe then recursively call the function for all safe cases from 0 to 9. if any recursive call returns true, end the loop and return true. If no recursive call returns true then return false.
4.If there is no unassigned location then return true.
