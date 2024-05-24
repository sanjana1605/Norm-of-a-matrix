# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1. Get the input matrix using np.array()

2. Find the 2-norm of the matrix using np.linalg.norm()

3. Print the norm of the matrix in two decimal places.
## Program:
```
Program to find 1-norm of a matrix.
Developed by:SANJANA SRI N
RegistrationNumber:2305003007
'''
1-Norm of a Matrix

import numpy as np
mat =np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)

# 2-Norm of a Matrix

import numpy as np
mat = np.array(eval(input())
ans = np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)

# Infinity Norm of a Matrix

import numpy as np
mat = np.array(eval(input())
ans = np.linalg.norm(mat,np.inf)
Norm_of_matrix = "{:.2f}.format(ans)
print(Norm_of_matrix)





```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/sanjana1605/Norm-of-a-matrix/assets/155608340/3023cd21-a121-439e-b277-79b16a81866e)



### 2-Norm of a Matrix
![image](https://github.com/sanjana1605/Norm-of-a-matrix/assets/155608340/dbf8a326-05c9-4ea2-919c-9d2fd0d3ab36)



### Infinity Norm of a Matrix
![image](https://github.com/sanjana1605/Norm-of-a-matrix/assets/155608340/90bad9ca-6274-4d6f-be81-b091a9ed64d2)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
