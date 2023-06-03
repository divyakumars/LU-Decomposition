# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.
2. Get input from user and print L and U matrix by 'print' .
3. Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.
4. print the variable 'X'


## Program:
(i) To find the L and U matrix
```
Program to find L and U matrix using LU decomposition.
Developed by: DIVYA K
RegisterNumber: 212222230035

import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
P,L,U=lu(a)
print(L)
print(U)
```

(ii) To find the LU Decomposition of a matrix
```
Program to find the LU Decomposition of a matrix.
Developed by: DIVYA K
RegisterNumber: 212222230035

import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=eval(input())
b=eval(input())
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)
```

## Output:
(i) To find the L and U matrix
![image]![image](https://github.com/divyakumars/LU-Decomposition/assets/119393621/d51f0b32-23f2-4621-8201-69c926feaa46)


(ii) To find the LU Decomposition of a matrix
![image]![image](https://github.com/divyakumars/LU-Decomposition/assets/119393621/b0ac4da5-d01c-4aec-ab73-39406f73a4ef)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

