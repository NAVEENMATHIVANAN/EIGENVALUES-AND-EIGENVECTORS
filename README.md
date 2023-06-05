# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy library: import numpy as np
### Step 2: 
Create a 3x3 numpy array A with the given values: A = np.array([[2,-3,0],[2,-5,0],[0,0,3]])
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
Print the values of evalues and evector using the print() function: print("Eigen values are {} and Eigen Vectors are {}".format(evalues,evector))
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: NAVEEN KUMAR M
#RegisterNumber: 212222110028

import numpy as np
A= np.array([[2,-3,0],[2,-5,0],[0,0,3]])
evalues , evector = np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(evalues,evector))
```
## Output:

![image](https://github.com/NAVEENMATHIVANAN/EIGENVALUES-AND-EIGENVECTORS/assets/119394582/190c9b4d-09ef-4cd6-a375-82ae3f0839dc)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
