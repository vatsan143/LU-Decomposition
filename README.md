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
/*
Program to find the L and U matrix.

Developed by: SRIVATSAN G

RegisterNumber: 212223230216
*/


```
import numpy as np 
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u= lu(a)
print(l)
print(u)
```


(ii) To find the LU Decomposition of a matrix
/*
Program to find the LU Decomposition of a matrix.

Developed by:  SRIVATSAN G

RegisterNumber: 212223230216
*/



````
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input ()))
b=np.array(eval(input ()))
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print (x)
````


## Output:
![Screenshot 2024-05-09 153751](https://github.com/vatsan143/LU-Decomposition/assets/147368204/920f174c-e537-4a89-9f4a-9ac8604b1b3b)
![Screenshot 2024-05-09 153807](https://github.com/vatsan143/LU-Decomposition/assets/147368204/d4960235-3319-4556-8336-7f6c2094b960)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

