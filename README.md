# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import numpy as np
2. from scipy package import lu
3. get input from the user
4. print result

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: G.Hindhu 
RegisterNumber: 23014493


import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U = lu(A)
print(L)
print(U)
/*
```

(ii) To find the LU Decomposition of a matrix
```
/*
'''
Program to find the LU Decomposition of a matrix.
Developed by:G.Hindhu 
RegisterNumber: 23014493

'''
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu, piv = lu_factor(A)
x = lu_solve((lu, piv), b)
print (x)
*/
```
## Output:
(i) To find the L and U matrix
![Alt text](<Screenshot 2023-12-29 103207-1.png>)
(ii) To find the LU Decomposition of a matrix
![Alt text](<Screenshot 2023-12-29 103233.png>) (ii) To find the LU Decomposition of a matrix

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

