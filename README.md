# EX-04-EIGENVALUES-AND-EIGENVECTORS
## DATE:
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation.
### Step 2: 
Prepare the lists from each equations and assign in np.array()
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: G Leka Sri
#RegisterNumber: 212223100025
import numpy as np
A = np.array([[2,2],[1,3]])
values, vectors = np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```

## Output:
![Screenshot 2024-09-04 204118](https://github.com/user-attachments/assets/10322103-f3c0-493c-b901-7b5fcb1b6ab9)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
