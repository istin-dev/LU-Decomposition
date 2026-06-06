# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. 
2. 
3. 
4. 

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
'''Program to solve a matrix using LU decomposition.
Developed by: Istin B
Register Number: 212223040068'''

import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"

import numpy as np
from scipy.linalg import lu
InputMatrix=np.array(eval(input()),dtype='i')
piv,Lmatrix,Umatrix=lu(InputMatrix)
print(Lmatrix)
print(Umatrix)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
'''
Program to solve a matrix using LU decomposition.
Developed by: Istin B
Register Number: 212223040068
'''
import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
AMatrix=np.array(eval(input()),dtype='i')
BMatrix=np.array(eval(input()),dtype='i')
XMatrix=lu_factor(AMatrix)
Solution=lu_solve(XMatrix,BMatrix)
print(Solution)
```

## Output:
![lu decomposition]()
<img width="1510" height="542" alt="image" src="https://github.com/user-attachments/assets/17efe606-aa45-443d-a09a-6108becf535d" />
<img width="1381" height="322" alt="image" src="https://github.com/user-attachments/assets/5be1f463-efa9-4f74-b451-dad93bc2e48f" />




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

