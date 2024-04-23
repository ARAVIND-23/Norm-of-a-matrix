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
```Python
# Register No:
# Developed By:
# 1-Norm of a Matrix

#Program to find the one norm matrix
#Developed by: ARAVIND G
#Register number: 212223240011

import numpy as np
matrix=eval(input())
one_matrix=np.linalg.norm(matrix,1)
print("{:.2f}".format(one_matrix))




# 2-Norm of a Matrix
#Program to find 2-norm of a matrix.
#Developed by: ARAVIND G
#RegisterNumber: 212223240011

import numpy as np
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,2)
print("{:.2f}".format(two_matrix))






# Infinity Norm of a Matrix

#program to find the infinity of a matrix
#Developed by: ARAVIND G
#Register number: 212223240011

import numpy as np
matrix=eval(input())
one_matrix=np.linalg.norm(matrix,np.inf)
print("{:.2f}".format(one_matrix))



```
## Output:
### 1-Norm of a Matrix
![Screenshot 2024-04-23 115215](https://github.com/ARAVIND-23/Norm-of-a-matrix/assets/138970182/e9c63c62-4c73-4663-be22-6dc6b57c33f1)

### 2-Norm of a Matrix
![Screenshot 2024-04-23 115227](https://github.com/ARAVIND-23/Norm-of-a-matrix/assets/138970182/f0d381e3-e938-4dd1-8b73-9ae339a249b2)


### Infinity Norm of a Matrix
![Screenshot 2024-04-23 115235](https://github.com/ARAVIND-23/Norm-of-a-matrix/assets/138970182/3957a797-9fab-4b09-a1bf-6c1baefeaad0)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
