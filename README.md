# LU Decomposition 

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

