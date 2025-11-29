# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import library Numpy as np.
### Step 2: Define the matrix with the given values.
### Step 3: Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Print the results using formatted string.

## Program:
```
import numpy as np
A=np.array([
        [-2,2,-3],
        [2,1,-6],
        [-1,-2,0]
])
eigval,eigvec=np.linalg.eig(A)
print(f"Eigen values are {eigval} and Eigen Vectors are {eigvec}")
```
## Output:
<img width="1477" height="801" alt="image" src="https://github.com/user-attachments/assets/ab438029-aedb-485a-92b0-5d1b9d16aa62" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
