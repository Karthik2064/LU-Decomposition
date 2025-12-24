# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import the numpy module to use the built-in functions for calculation
2. Prepare the lists from each linear equations and assign in np.array()
3. Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
4. End the program
   
## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: k.karthik
RegisterNumber: 25017589
*/
'''Program to find L and U matrix using LU decomposition.
Developed by: 
RegisterNumber: 
'''
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: k.karthik
RegisterNumber: 25017589
*/
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,pivot=lu_factor(A)
x=lu_solve((lu,pivot),B)
print(x)
```

## Output:
<img width="1920" height="1080" alt="Screenshot 2025-12-24 154528" src="https://github.com/user-attachments/assets/3178d321-7c96-45c6-a9b5-d4de6406f8ce" />
<img width="1920" height="1080" alt="Screenshot 2025-12-24 154549" src="https://github.com/user-attachments/assets/27db6cde-1afa-4de9-933d-abd6e9ca9aae" />
<img width="1920" height="1080" alt="Screenshot 2025-12-24 154601" src="https://github.com/user-attachments/assets/801aef1e-a34d-4fd4-94c1-a38041001f69" />
<img width="1920" height="1080" alt="Screenshot 2025-12-24 154639" src="https://github.com/user-attachments/assets/8684aa75-a90a-40fb-ada8-e162e5ab65c4" />






## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

