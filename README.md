# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import numpy as np
2.from scipy package import lu
3.get input from the user
4.Print result

## Program:
~~~
'''Program to find L and U matrix using LU decomposition.
Developed by: Rakshitha k
RegisterNumber: 23003887
'''
from scipy.linalg import lu
import numpy as np
arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U)


'''Program to solve a matrix using LU decomposition.
Developed by: 
RegisterNumber: 
'''
from scipy.linalg import lu_factor,lu_solve
import numpy as np
arr=eval(input())
constant=eval(input())
A=np.array(arr)
B=np.array(constant)
result=lu_factor(A)
solution=lu_solve(result,B)
print(solution)
~~~

## Output:
![image](https://github.com/RakshithaK11/LU-Decomposition/assets/139336455/1f36247b-b01f-4383-8fd6-46a89ca6523c)
![image](https://github.com/RakshithaK11/LU-Decomposition/assets/139336455/c8ac0730-7d17-41a9-81cb-af0918de4825)
![image](https://github.com/RakshithaK11/LU-Decomposition/assets/139336455/47fb0e72-81e5-4c51-a841-ccab6d35a3ba)
![image](https://github.com/RakshithaK11/LU-Decomposition/assets/139336455/28b7ec13-d046-4c72-9260-5fa8411268e2)





## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

