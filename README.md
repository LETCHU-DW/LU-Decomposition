# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
Step 1:
Import the required library (SciPy or similar library that supports LU decomposition).
Step 2:
Define the square matrix.
Step 3:
Apply the LU decomposition function to the matrix to obtain L and U (and P if required).
Step 4: Display the matrices L and U (and P, if used)
## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: LAKSHMI NARASIMAN K
RegisterNumber: 21225230146
*/

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
Developed by: LAKSHMI NARASIMAN K
RegisterNumber: 21225230146
*/

import numpy as np
from scipy.linalg import lu factor, lu solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,pivot= lu factor(A)
x=lu solve((lu,pivot),B)
Print(x)
```

## Output:

(i)

<img width="915" height="795" alt="Screenshot 2026-02-12 085437" src="https://github.com/user-attachments/assets/fd77053a-add4-4dc9-8f0d-8501c0c24541" />

(ii)

<img width="789" height="655" alt="Screenshot 2026-02-12 085457" src="https://github.com/user-attachments/assets/08ba249b-61dc-4f61-9bb4-422cd9b84d9c" />

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

