# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
Step 1:
Import numpy library using import statement.

Step 2:
From scipy package import lu().

Step 3:
Get input from user and pass it as an array.

Step 4:
Get P, L, U matrix using lu()

Step 5:
Print L and U matrix

## Program:

(i) To find the L and U matrix
```
Program to find the L and U matrix.
Developed by: 
RegisterNumber: 
Program to find L and U matrix using LU decomposition.
Developed by: KEERTHI VASAN A
RegisterNumber: 212222240048

import numpy as np
from scipy.linalg import lu
arr=np.array(eval(input()))
P,L,U=lu(arr)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
Program to find the LU Decomposition of a matrix.
Developed by: KEERTHI VASAN A
RegisterNumber: 212222240048
import numpy as np
from scipy.linalg import lu_factor,lu_solve
arr=np.array([[3,2,7],[2,3,1],[3,4,1]])
B=np.array([4,5,7])
LU,P=lu_factor(arr)
res=lu_solve((LU,P),B)
print(res)
```

## Output:
## L AND U MATRIX 
![Screenshot (132)](https://user-images.githubusercontent.com/107488929/234479100-16051608-2dd1-47fa-8ace-c5b5cfce747a.png)
## LU DECOMPOSITION

![Screenshot (133)](https://user-images.githubusercontent.com/107488929/234479481-9d6c2190-27ac-4c65-8fa7-b14f15289b7b.png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

