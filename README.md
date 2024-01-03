# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.First,import numpy.
2.Import scipy.linalg and import lu for lu decomposition.
3.Get the input from the user.
4.Print the result.

## Program:
(i) To find the L and U matrix

### Program to find L and U matrix using LU decomposition.
### Developed by: ARUNMOZHI VARMAN T
### RegisterNumber: 212223230022
```
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
### Program to find L and U matrix using LU decomposition.
### Developed by: ARUNMOZHI VARMAN T
### RegisterNumber: 212223230022
```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),b)
print(x)
```
## Output:
To find the L and U matrix
![image](https://github.com/ArunmozhiVarmanT/LU-Decomposition/assets/144870523/cc58b4d5-33a9-4410-8e3a-fd67593d0e62)

To find the LU Decomposition of a matrix
![image](https://github.com/ArunmozhiVarmanT/LU-Decomposition/assets/144870523/dc9d2324-1317-49e8-a505-3f309baf59a8)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

