# Recursion-And-Algorithmic-Puzzles
Functions that rely on recursion or have a puzzle-like quality, including searches and sorting challenges.

Functions written by Dr Eleni Christoforidou in MATLAB R2022b.

## recursive_max

This is a recursive function that finds the maximum element in a vector. The sole output argument is the maximum value in the input vector.

## spiral_diag_sum

The function takes an odd positive integer n as an input and computes the sum of all the elements in the two diagonals of the n-by-n spiral matrix.

## move_me

The first input argument v is a row-vector, while the second input argument a is a scalar. The function moves every element of v that is equal to a to the end of the vector. If a is omitted, the function moves occurrences of zeros.

## dial

Each number on telephone keypads, except 0 and 1, corresponds to a set of uppercase letters as shown in this list: 2 ABC, 3 DEF, 4 GHI, 5 JKL, 6 MNO, 7 PQRS, 8 TUV, 9 WXYZ. Hence, a phone-number specification can include uppercase letters and digits. The function takes as its input argument a character array of length 16 or less that includes only these characters and returns as its output argument the telephone number as a uint64. The phone number must never start with 0. If the input contains any illegal characters, the function returns 0.

## find_zero

The first input argument is a “function handle”. All other arguments are scalar numbers, and x1 must be less than x2. The function finds an x that lies in the range from x1 to x2 such that after the command, y=f(x), is executed inside the function find_zero, y is approximately zero as defined by abs(y)<1e-10. The function f has one scalar input and one scalar output, and a plot of its values crosses the x-axis exactly once between x1 and x2 (see attached figure). It is the responsibility of the user to call the function with arguments that obey these rules.

![image](https://github.com/eleni-chr/Recursion-And-Algorithmic-Puzzles/blob/master/figure_find_zero.png)

## sort3

The function takes a 3-element vector as input and returns the three elements of the vector as three scalar output arguments in non-decreasing order.
