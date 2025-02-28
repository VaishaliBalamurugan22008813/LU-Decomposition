# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy library as np
2. Create a matrix using np.array()
3. Using scipy.linalg.lu() find L and U, also using scipy.linalg.lu_solve() get the result for LU
Decomposition
4. Get the output and end the program

## Program:
(i) To find the L and U matrix
```

Program to find the L and U matrix.
Developed by: VAISHALI BALAMURUGAN
RegisterNumber: 22008813

import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P, L, U = lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```

Program to find the LU Decomposition of a matrix.
Developed by: VAISHALI BALAMURUGAN
RegisterNumber: 22008813

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu, piv = lu_factor(A)
x = lu_solve((lu, piv), b)
print(x)
```

## Output:
![LU](https://user-images.githubusercontent.com/119390134/214333649-d10ad3d6-99e7-4a11-89b9-2af47b88a077.png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

