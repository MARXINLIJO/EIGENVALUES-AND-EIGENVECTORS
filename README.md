# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : import the required libraries
### Step 2: define a matrix A
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: display the calculates eign values and eigen vectors

## Program:
```
 #Program to find the eigen values and eigen vectors.
#Developed by:Marxin Lijo M
#RegisterNumber:23013468
import numpy as np
a=[[4,2],[2,4]]
value,vectors=np.linalg.eig(a)
print("Eigen values are",value,"and Eigen Vectors are",vectors)
```
## Output:
![Screenshot 2023-12-24 220833](https://github.com/MARXINLIJO/EIGENVALUES-AND-EIGENVECTORS/assets/145742540/8659bbe4-a097-4000-9831-0cb5d5e56707)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
