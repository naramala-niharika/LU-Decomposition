# LU Decomposition without zero on the diagonal

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Start the program
2. Input the values
3. Display the program
4. Stop the program

## Program:
'''Program to find L and U matrix using LU decomposition.
Developed by:N.Niharika
RegisterNumber:21500912
'''

# To print L and U matrix
import numpy as np

from scipy.linalg import lu

A=np.array(eval(input()))

P,L,U=lu(A)

print(L)

print(U)

'''Program to solve a matrix using LU decomposition.
Developed by:N.Niharika
RegisterNumber:21500912
'''

# To print X matrix (solution to the equations)
import numpy as np

from scipy.linalg import lu_factor, lu_solve

A=(eval(input()))

B=(eval(input()))

lu,piv=lu_factor(A
)
X=lu_solve((lu, piv), B)

print(X)

## Output:
![lu decomposition]()


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

