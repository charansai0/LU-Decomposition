# LU Decomposition without zero on the diagonal

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm

Step 1:
Import the numpy module to use the built-in functions for calculation

Step 2:
Prepare the lists from each linear equations and assign in np.array()

Step 3:
Using the np.linalg.solve(), we can find the solutions.

Step 4:
End the program

## Program:

#Program to find the LU Decomposition of a matrix.

#Developed by: v.charan sai

#RegisterNumber: 21003158

#To print L and U matrix

import numpy as np

import scipy

from scipy.linalg import lu

A = np.array (eval(input()))

P,L,U = lu(A)

print(L)

print(U)

## Output:
![lu decomposition]()


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

