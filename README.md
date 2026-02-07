# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import the numpy module to use the built-in functions for calculation
2. Prepare the lists from each linear equations and assign in np.array()
3. 
4. End the program

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: DHARSHAN BABU A
RegisterNumber:212225220023
'''
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)

print(L)

print(U)

```
(ii) To find the LU Decomposition of a matrix
```
 '''Program to solve a matrix using LU decomposition.
Developed by: DHARSHAN BABU A
RegisterNumber: 212252220023
'''
import numpy as np

from scipy.linalg import lu_factor,lu_solve
 
A=np.array(eval(input()))
 
B=np.array(eval(input()))
 
lu,pivot=lu_factor(A)

x=lu_solve((lu,pivot),B)

print(x)
```

## Output:

(i) To find the L and U matrix


<img width="1108" height="833" alt="image" src="https://github.com/user-attachments/assets/a6d2878d-a3df-40a5-bc63-64412e553e6f" />


<img width="1210" height="573" alt="image" src="https://github.com/user-attachments/assets/9577503f-ad29-44f9-a1cd-d88d306878d7" />

 (ii) To find the LU Decomposition of a matrix


 <img width="745" height="814" alt="image" src="https://github.com/user-attachments/assets/4d80365c-7179-4b0a-8cba-c81662451574" />


 <img width="1195" height="283" alt="image" src="https://github.com/user-attachments/assets/85021c50-3c54-4f94-88c2-c572138f6e35" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

