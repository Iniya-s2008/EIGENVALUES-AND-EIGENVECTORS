# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each linear equations and assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Display and End the program.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: iNIYA S
#RegisterNumber:212225230104
import os
os.environ['OPENBLAS_NUM_THREADS']='1'
import numpy as np
matrix=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
eig_val,eig_vec=np.linalg.eig(matrix)
print("Eigen values are {} and Eigen Vectors are {}".format(eig_val,eig_vec))
```

## Output:
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/e997453c-ffef-4f4e-a734-1b206250074d" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/cf1a97c1-3fa2-4364-a100-23c0be627a8b" />

[out4.pdf](https://github.com/user-attachments/files/27386161/out4.pdf)


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
