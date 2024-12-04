# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import required libraries numpy and scipy.linalg.
2. Input the matrix/matrices using eval(input()).
3. Perform LU decomposition using lu() or solve equations using lu_factor() and lu_solve().
4. Print the results L and U matrices or solution X matrix.

## Program:
(i) To find the L and U matrix
```
Developed by: Sharan Kumar G
RegisterNumber:24003909 
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)
```
(ii) To find the LU Decomposition of a matrix
```
Developed by: Sharan Kumar G
RegisterNumber: 24003909
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)
```

## Output:
![image](https://github.com/user-attachments/assets/785f08ec-7528-40a3-9b34-5b0ca0596537)
![image](https://github.com/user-attachments/assets/6037ef3c-f64a-459a-a033-ae1a720d5242)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

