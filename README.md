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
```
'''Program to find L and U matrix using LU decomposition.
Developed by: ARAVINDAN D
RegisterNumber: 21223240012
'''

import numpy as np
from scipy.linalg import lu
a = np.array(eval(input()))
P,L,U =lu(a)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```

'''Program to find  X matrix (solution to the equations)
Developed by: ARAVINDAN D
RegisterNumber: 21223240012
'''
# To print X matrix (solution to the equations)

import numpy as np
from scipy .linalg import lu_factor , lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))

lu,piv = lu_factor(a)
x= lu_solve((lu,piv),b)
print(x)

```

## Output:
![lu decomposition]()


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

