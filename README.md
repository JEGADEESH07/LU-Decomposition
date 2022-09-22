# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Read the elements of augmented matrix into arrays a and b
2.Calculate elements of L and U
3.Print elements of L and U
4.Find V by solving LV = B by forward substitution
5.Find X by solving UX = V by backward substitution
6.Print Array X as the solution

## Program:
``` python
'''Program to find L and U matrix using LU decomposition.
Developed by: JEGADEESH S
RegisterNumber: 22004355
'''
from scipy.linalg import lu
a=eval(input())
P,L,U=lu(a)
print(L)
print(U)
```

## Output:
![OUTPUT](output4.png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

