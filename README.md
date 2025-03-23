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
Prepare the lists from each equations and assign in np.array()
### Step 3:
Using the np.linalg.matrix_rank(), we can find the inverse of the given matrix
### Step 4:
End the program
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Khamalraaj S
#RegisterNumber:212224230122
import numpy as np
A=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
Eigen_Values,Eigen_Vectors=np.linalg.eig(A)
print("Eigen values are",Eigen_Values,"and Eigen Vectors are",Eigen_Vectors)
```

## Output:
![{2DAC77F5-C5B4-4DFF-B527-EDAB398A5889}](https://github.com/user-attachments/assets/6beea5b5-fd7f-493f-be93-712bb0252d62)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
