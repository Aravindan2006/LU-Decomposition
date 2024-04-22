# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
Step1 : Import the module numpy and assign numpy as np.

Step 2: Create an variable named 'a' and use np.array(eval(input())) for the matrix values by
        first list as first row and so on.
        
Step 3: Using the  from scipy.linalg,  of the given matrix.

Step 4: Print the LU decomposition matrix


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

import numpy as np
from scipy .linalg import lu_factor , lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))

lu,piv = lu_factor(a)
x= lu_solve((lu,piv),b)
print(x)

```

## Output:
(i) To find the L and U matrix
![Screenshot 2024-04-22 154240](https://github.com/Aravindan2006/LU-Decomposition/assets/151760062/50bf3ff0-9c13-43e0-a607-0af910f88145)

(ii) To find the LU Decomposition of a matrix
![Screenshot 2024-04-22 154258](https://github.com/Aravindan2006/LU-Decomposition/assets/151760062/8a781049-342a-4bb4-847a-ebdae4139aff)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

