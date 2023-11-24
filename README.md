# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
## step-1:
Start the program.
## step-2:
End the program.

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: MUKESH R
RegisterNumber: 23006020
'''
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: MUKESH R
RegisterNumber: 23006020
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=eval(input())
b=eval(input())
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)
```

## Output:
(i) To find the L and U matrix.
![Screenshot 2023-11-24 111043](https://github.com/2005Mukesh/LU-Decomposition/assets/138849308/3d8507e0-1e2a-44f9-a7b5-439b27027315)

(ii) To find the LU Decomposition of a matrix.
![Screenshot 2023-11-24 111055](https://github.com/2005Mukesh/LU-Decomposition/assets/138849308/4289eefe-8f22-4c6d-82c2-40c4b9a7e11c)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

