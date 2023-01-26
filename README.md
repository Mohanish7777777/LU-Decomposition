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
```python
'''Program to find L and U matrix using LU decomposition.
Developed by: Mohanish.K
RegisterNumber:22002294
'''
import numpy as np #forn numpy inport array
from scipy.linalg import lu
arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U) 
*/
```
(ii) To find the LU Decomposition of a matrix
```python
'''Program to solve a matrix using LU decomposition.
Developed by: Mohanish.K
RegisterNumber: 22002294
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=eval(input())
res=lu_factor(A)
solution=lu_solve(res,B)
print(solution)
```

## Output:
(i)
![image](https://user-images.githubusercontent.com/111619160/214814982-d82f2bda-0c63-4ce9-b2b7-66fc7177c747.png)
(ii)
![image](https://user-images.githubusercontent.com/111619160/214815063-6904d530-31f8-4b46-8ca5-4f2f3213f74e.png)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

