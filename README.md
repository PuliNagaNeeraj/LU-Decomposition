# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import the numpy as np
2.from scipy.linalg import lu
3.enter the lists from each linear equationa and assgin in np.array()
4.using lu( )and store it in three variables
5.print the L and U matrix
6.end the program
   

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: PULI NAGA NEERAJ
RegisterNumber: 23004033
*/
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
P,L,U=lu(a)
print(L)
print(U)
```


(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: PULI NAGA NEERAJ
RegisterNumber: 23004033
*/
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)
```

## Output:
![lu decomposition]()
![Screenshot 2023-12-24 132307](https://github.com/PuliNagaNeeraj/LU-Decomposition/assets/138849173/9f487f1b-ea9e-4a18-88d7-a5beb77375f4)
![Screenshot 2023-12-24 132336](https://github.com/PuliNagaNeeraj/LU-Decomposition/assets/138849173/842998ec-dc32-4d37-9dcf-f29947697329)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

