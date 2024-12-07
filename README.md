# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Start the program
2.Import the necessary libraries(numpy,scipy.linalg)
3.Define the matrix using numpy
4.End the program 

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by:MITHUN S
RegisterNumber: 24901037
*/
```
```
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U = lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: MITHUN S
RegisterNumber: 24901037
*/
```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
AMatrix=np.array(eval(input()),dtype='i')
BMatrix=np.array(eval(input()),dtype='i')
XMatrix=lu_factor(AMatrix)
solution=lu_solve(XMatrix,BMatrix)
print(solution)
```

## Output:
OUTPUT(image-1.png)
OUTPUT(image-2.png)
## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

