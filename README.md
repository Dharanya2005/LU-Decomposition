# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:
1. Import the numpy module to use the built_in function for calculation
2. Prepare the lists from each linear equations and assign in np.array()
3. Using the np.linalg.solve(we ca find the solutions)
4. End the program


## Program:
(i) To find the L and U matrix
```
Program to find L and U matrix using LU decomposition.
Developed by:DHARANYA.N 
RegisterNumber: 23006980
from scipy.linalg import lu
import numpy as np
arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
Program to solve a matrix using LU decomposition.
Developed by:DHARANYA.N
RegisterNumber: 23006980
from scipy.linalg import lu_factor,lu_solve
import numpy as np
arr=eval(input())
constant=eval(input())
A=np.array(arr)
B=np.array(constant)
result=lu_factor(A)
solution=lu_solve(result,B)
print(solution)
```


## Output:
i)
![Screenshot 2023-11-29 184908](https://github.com/Dharanya2005/LU-Decomposition/assets/145742468/9e5022c6-271b-4dee-8363-c31f02006455)
ii)
![Screenshot 2023-11-29 184959](https://github.com/Dharanya2005/LU-Decomposition/assets/145742468/c51d8b3e-c076-40f5-b155-56ba31a3577d)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

