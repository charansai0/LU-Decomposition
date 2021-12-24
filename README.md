# LU Decomposition without zero on the diagonal

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm

Step 1:
start the program

Step 2:
Import the numpy  module to use the built-in functions for calculation

Step 3:
Prepare the lists from each linear equations and assign in np.array()

Step 4:
Using the np.linalg.solve(), we can find the solutions.

Step 5:
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
![lu decomposition](https://github.com/charansai0/LU-Decomposition/blob/main/Screenshot%20(156).png?raw=true)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.




## AIM:
To write a program to slove the  matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm

Step 1:
start the program

Step 2:
Import the numpy  module to use the built-in functions for calculation

Step 3:
Prepare the lists from each linear equations and assign in np.array()

Step 4:
Using the np.linalg.solve(), we can find the solutions.

Step 5:
End the program

## Program:

#Program to find the LU Decomposition of a matrix.

#Developed by: v.charan sai

#RegisterNumber: 21003158

#To print X matrix (solution to the equations)

import numpy as np

from scipy.linalg import lu_factor, lu_solve

A=(eval(input()))

B=(eval(input()))

lu,piv=lu_factor(A)

X=lu_solve((lu, piv), B)

print(X)

## Output:
![lu decomposition](https://github.com/charansai0/LU-Decomposition/blob/main/Screenshot%20(159).png?raw=true)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.



