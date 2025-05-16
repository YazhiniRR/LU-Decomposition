# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
## To find the L and U matrix
Step 1:
Input matrix A from the user.Convert input to a NumPy array.

Step 2:
Apply LU decomposition: P, L, U = lu(A).

Step 3:
Extract lower triangular matrix L.Extract upper triangular matrix U and print both L and U.

Step 4:
End the program
## Algorithm
## To find the LU Decomposition of a matrix
Step 1:
 Input matrix A and vector b from the user.Convert both inputs into NumPy arrays.

Step 2:
  Perform LU factorization using lu_factor(A) to get LU matrix and pivot indices.
  
Step 3:
   Solve the linear system Ax = b using lu_solve((lu, piv), b).

Step 4:
  Output the solution vector X.
  
## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: YAZHINI R R
RegisterNumber: 212224100063

import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: YAZHINI R R 
RegisterNumber: 212224100063

import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
X=lu_solve((lu, piv),b)
print(X)
```

## Output:
![Screenshot 2025-05-13 160546](https://github.com/user-attachments/assets/99595e5b-a979-48c3-a4f3-59bb300d94b5)
![Screenshot 2025-05-13 160557](https://github.com/user-attachments/assets/a9c3a68c-4241-48dd-8d75-23a5733832ce)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

