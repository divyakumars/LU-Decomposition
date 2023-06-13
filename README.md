# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
## step1:
Import numpy as np
## step2:
Import library called 'scipy' to solve the lu decomposition.
 ## step3:
 Import lu_factor and lu_solve libraries.
## step4:
Get the input to solve the lu decomposition.
## step5:
Print the result obtained.


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

