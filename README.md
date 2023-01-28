# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
import numpy as any variable
### Step 2: 
let assume any variable
### Step 3:
 Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
print eigen values and eigen vectors

```
## PROGRAM:

#Program to find the eigen values and eigen vectors.
#Developed by: Anbuselvam A
#RegisterNumber:22009081
import numpy as np 
a=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
value,vector=np.linalg.eig(a)
print(f'Eigen values are {value} and Eigen Vectors are {vector}')
```
## Output:
![output](./Screenshot%20(35).png)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
