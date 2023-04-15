# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculations
### Step 2: 
Prepare  the lists from each equations and assign in np.array()
### Step 3:
 Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program

## Program:

```
#Program to find the eigen values and eigen vectors.
#Developed by:N.Swetha
#RegisterNumber:212222110050
import numpy as np
A=np.array(([2,2],[1,3]))
evalues,evector=np.linalg.eig(A)S
print("Eigen values are {} and Eigen Vectors are {}".format(evalues,evector))
```
## Output:
![Screenshot (74)](https://user-images.githubusercontent.com/122199934/232199159-ec97559d-5767-4bf4-b673-94ae0a4d1886.png)


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
