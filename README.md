# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation.
### Step 2: Prepare the lists from each equations and assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the program

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: R mounish vamsi kumar
#RegisterNumber: 24003774
import numpy as np
a = np.array([[2,-3,0],[2,-5,0],[0,0,3]])
b,c=np.linalg.eig(a)
print(f"Eigen values are {b} and Eigen Vectors are {c}")
```
## Output:
<img width="1920" height="1140" alt="Screenshot 2026-02-07 110032" src="https://github.com/user-attachments/assets/520bb6c2-2c2b-46e1-9d3c-50d074f8e463" />


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
