# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm

1.Import the numpy module to use the built-in functions for calculation
2.Import the numpy module to use the built-in functions for calculation
3.Using the np.linalg.norm,we get result
4.End the program

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by:DHARSHAN PR\T 
RegisterNumber:23005803 
*/
```
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by:DHARSHAN PT 
RegisterNumber:23005803 
*/
```
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu, piv = lu_factor(A)
x = lu_solve((lu, piv), b)
print (x)

## Output:

![Screenshot 2024-01-01 231126](https://github.com/dharshanpt/LU-Decomposition/assets/138849376/436afe45-865b-4e07-8bab-07ae7e9d1a7f)

![Screenshot 2024-01-01 231154](https://github.com/dharshanpt/LU-Decomposition/assets/138849376/e20578ce-33bf-4ebb-b8dc-9c70d7cdb8e3)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

