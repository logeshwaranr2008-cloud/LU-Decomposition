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
4.Use lu(),lu_solve(),lu_factor() to get the solutions
5.End the program

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: R.Logeshwaran
RegisterNumber: 212225040205
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: R.Logeshwaran
RegisterNumber: 212225040205
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,pivot=lu_factor(A)
x=lu_solve((lu,pivot),B)
print(x)
*/
```

## Output:
<img width="1850" height="949" alt="Maths Exp-5(a)" src="https://github.com/user-attachments/assets/8113d57c-1d13-4c97-9bc7-c9ffe3d376d2" />
<img width="1849" height="833" alt="Maths Exp-5(b)" src="https://github.com/user-attachments/assets/67314e7c-a9d1-4ff7-afcc-3c73b9f65026" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

