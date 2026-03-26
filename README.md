# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
### Step 2: 
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 

## Program:
import numpy as np

a = np.array([[2, 2],
              [1, 3]])

eigen_values, eigen_vectors = np.linalg.eig(a)

print("Eigen values are", eigen_values, "and Eigen Vectors are", eigen_vectors)
## Output:
<img width="1270" height="212" alt="image" src="https://github.com/user-attachments/assets/edfc7ebb-9fe4-46e2-9064-374daf497004" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
