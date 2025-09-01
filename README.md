# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
(i)

1. import numpy as np and from scipy.linalg import lu
2. using np.array store matrix in variable matrix
3. using lu(),we can find lower triangular matrix and upper triangular matrix
4. print the lower triangular matrix and upper triangular matrix

(ii)

1.  import numpy as np and from scipy.linalg import lu_factor,lu_solve
2.  using np.array store matrix in variable matrix
3.  using lu_solve(),we can find LU decomposition of matrix
4.  using lu_solve(),we can find the solution to linear equation AX=B where A is matrix,X is unknown vector,B is the constant matrix
5.  print the solution of vector X

   
## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: 
RegisterNumber: 
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
Developed by: 
RegisterNumber: 
*/
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
l,p=lu_factor(a)
x=lu_solve((l,p),b)
print(x)

```

## Output:

(i)

<img width="1250" height="967" alt="Screenshot 2025-09-01 111259" src="https://github.com/user-attachments/assets/1a06b187-6e22-43b2-a30b-9e4c9a2bafeb" />

(ii)

<img width="1507" height="939" alt="Screenshot 2025-09-01 094812" src="https://github.com/user-attachments/assets/2225d0d9-4779-46d6-be15-a770f03a3a5e" />

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

