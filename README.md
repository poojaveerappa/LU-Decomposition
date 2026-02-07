# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Start the program
2. Import the necessary libraries(numpy,scipy.linalg)
3. Define the matrix using numpy
4. Use lu(),lu_solve(),lu_factor() to get the solutions
5. End the program


## Program:
(i) To find the L and U matrix
```
/*
Program to find L and U matrix using LU decomposition:

import numpy as np
from scipy.linalg import lu 
A=np.array(eval(input()))
p,l,u=lu(A)
print(l)
print(u)

Developed by: Pooja V
RegisterNumber: 212225040302
*/

```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to solve a matrix using LU decomposition:

import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,pivot=lu_factor(A)
x=lu_solve((lu,pivot),B)
print(x)

Developed by:Pooja V 
RegisterNumber: 212225040302

*/
```

## Output:
<img width="839" height="574" alt="Screenshot 2026-02-07 082634" src="https://github.com/user-attachments/assets/cb79c430-c0e9-4a0d-a9c9-c1808c977837" />
<img width="831" height="454" alt="Screenshot 2026-02-07 082644" src="https://github.com/user-attachments/assets/403f3af2-ea0b-4d30-8ae2-367482e750ff" />




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

