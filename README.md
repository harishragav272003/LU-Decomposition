# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
Define the package as scipy.linalg import lu.
Get input from user and print L and U matrix by 'print'.
Define a package as "from scipy.linalg import lu_factor,lu_solve" and create the variable as "X" include the package in that variable. 4.Print the variable "X".

## Program:
(i) To find the L and U matrix
```
'''
Program to find the L and U matrix.
Developed by: HARISH RAGAV S
RegisterNumber: 212222110013
'''
import numpy as np
from scipy.linalg import lu
arr=np.array(eval(input()))
P,L,U=lu(arr)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''
Program using LU Decomposition to solve a matrix.
Developed by: HARISH RAGAV S
RegisterNumber: 212222110013

'''
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=eval(input())
B=eval(input())
lu,piv=lu_factor(A)
X=lu_solve((lu,piv),B)
print(X)

```

## Output:
![image](https://github.com/harishragav272003/LU-Decomposition/assets/119345345/745659fc-28c1-4c9f-a642-aeb66f1dd0be)



![image](https://github.com/harishragav272003/LU-Decomposition/assets/119345345/e618a225-4ea1-4676-a958-59af93a87da6)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

