# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
Import the numpy module to use the built-in functions for calculation
### Step 2:
Prepare the lists from each linear equations and assign in np.array()
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by:KARTHIKEYAN A
#RegisterNumber:25016466
import numpy as np
a = np.array([[-2, 2, -3],[2, 1, -6],[-1, -2, 0]])
eigenvalues, eigenvectors = np.linalg.eig(a)
print(f"Eigen values are {eigenvalues} and Eigen Vectors are {eigenvectors}")
```
## Output:
<img width="1264" height="835" alt="Screenshot 2025-11-19 135609" src="https://github.com/user-attachments/assets/e6eaaaf4-26e9-4add-82e7-ab1f01560a64" />

##Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
