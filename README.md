# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :Import the numpy module to use the built-in functions for calculation. 
### Step 2: Prepare the lists from each equations and assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the program.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: R.MAHALAKSHMI
#RegisterNumber:212223230117

import numpy as np
# Define the matrix
A = np.array([[2, -3, 0],[2, -5, 0],[0, 0, 3]])
Eigenvalues, Eigenvectors = np.linalg.eig(A)
print("Eigen values are",Eigenvalues, "and Eigen Vectors are",Eigenvectors)
```
## Output:
![image](https://github.com/Maharavi2006/EIGENVALUES-AND-EIGENVECTORS/assets/154535981/e417e923-d746-4c4f-b84c-f2019fab0c31)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
