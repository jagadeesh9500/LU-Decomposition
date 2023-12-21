# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. read the elements of augmented matrix into array a and b
2.calculate elements of L and U
3.print L and U matrix
4.find V by solving LV = B by forwrd substitution
5.find X by solving UX = V by backward substitution
6.print array X as the solution
   

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: JAGADEESH P
RegisterNumber: 23013534
'''
from scipy.linalg import lu
import numpy as np
arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: JAGADEESH P
RegisterNumber:23013534 
'''
from scipy.linalg import lu_factor,lu_solve
import numpy as np
arr=eval(input())
constant=eval(input())
A=np.array(arr)
B=np.array(constant)
res=lu_factor(A)
solution=lu_solve(res,B)
print(solution)
*/
```

## Output:
![image](https://github.com/jagadeesh9500/LU-Decomposition/assets/149087921/0de9ed6e-f3c6-4fc4-a5dd-2c5c7faf9be9)
![image](https://github.com/jagadeesh9500/LU-Decomposition/assets/149087921/616618c5-0360-4ca6-9d5d-a2f629c5b24e)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

