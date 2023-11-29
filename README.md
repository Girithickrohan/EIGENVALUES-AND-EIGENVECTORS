# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Check if the matrix is square
### Step 2: Compute eigenvalues and eigenvectors
### Step 3: Display eigenvalues and eigenvectors
### Step 4: Return eigenvalues and eigenvectors

## Program:
```
import numpy as np
matrix=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
eigenvalues,eigenvectors=np.linalg.eig(matrix)
print("Eigen values are",eigenvalues,"and Eigen Vectors are",eigenvectors)
```
## Output:

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
