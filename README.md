# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Read the elements of augmented matrix into arrays
2. calculate elements of L and U
3. Print elements of L and U
4. find V by solving LV=B by forword substitution

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

