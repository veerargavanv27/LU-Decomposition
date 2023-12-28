# LU Decomposition 
## AIM:
To write a program to find the LU Decomposition of a matrix.
## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm
1. Import the numpy module to use the built-in functions for calculation
2. Import the numpy module to use the built-in functions for calculation
3. Using the np.linalg.norm,we get result
4. End the program
## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: VEEARARAGAVAN V
RegisterNumber: 23004739
*/
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: 
RegisterNumber: 
*/
import numpy as np
from scipy.linalg import lu,solve
a=np.array(eval(input()))
b=np.array(eval(input()))
p,l,u=lu(a)
y=solve(l,np.dot(p,b))
x=solve(u,y)
print(x)
```
## Output:
![image](https://github.com/veerargavanv27/LU-Decomposition/assets/138955645/5f5a39b4-6664-46b9-9a27-6fbcb03df6b4)
![image](https://github.com/veerargavanv27/LU-Decomposition/assets/138955645/a08d28a4-4a58-4f72-9616-098832bf9013)
## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.
