# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy extension and scipy.linalg extension
2. Initialize the matix values
3. Use lu functions from imported extensions
4. Print the output

## Program:
(i) To find the L and U matrix
```
Program to find the L and U matrix.
Developed by: KEERTHIKA M P
RegisterNumber: 212223240071
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
Program to find the LU Decomposition of a matrix.
Developed by: KEERTHIKA M P
RegisterNumber: 212223240071
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),b)
print(x)
```

## Output:
(i) To find the L and U matrix
![Screenshot 2024-04-22 224820](https://github.com/Keerthika23013559/LU-Decomposition/assets/162658262/94c1af35-e32f-44ad-a778-244f4f9a1ca7)

(ii) To find the LU Decomposition of a matrix

![Screenshot 2024-04-22 224829](https://github.com/Keerthika23013559/LU-Decomposition/assets/162658262/654a58df-0536-4938-9ee4-853900d6ddff)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

