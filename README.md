# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy package 
2. Import lu from scripy.linalg   
3. Get the input of the array 
4. Print the output.

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: JEEVITHA S
RegisterNumber:212222100016 
'''
import numpy as np
from scipy.linalg import lu
arr=np.array(eval(input()))
P,L,U=lu(arr)
print(L)
print(U)
```
ii) LU Decomposition to solve a matrix.
```
'''Program to solve a matrix using LU decomposition.
Developed by: JEEVITHA S
RegisterNumber: 212222100016
'''
import numpy as np
from scipy.linalg import lu_factor,lu_solve
arr=np.array([[3,2,7],[2,3,1],[3,4,1]])
B=np.array([4,5,7])
LU,P=lu_factor(arr)
res=lu_solve((LU,P),B)
print(res)
```

## Output:
i)
![image](https://github.com/Jeevithha/LU-Decomposition/assets/123623197/7643ccc0-caf0-4982-a315-229091acf05c)

ii)
![image](https://github.com/Jeevithha/LU-Decomposition/assets/123623197/a0f7943f-f0fe-487c-b78a-da4da1e2f129)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

