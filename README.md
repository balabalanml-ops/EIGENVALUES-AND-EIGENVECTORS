<img width="1262" height="245" alt="image" src="https://github.com/user-attachments/assets/dedfa021-6dcc-411e-9e79-4f7c9b243a99" /># EIGENVALUES-AND-EIGENVECTORS
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

a= np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])

values,vectors=np.linalg.eig(a)

print('Eigen values are {} and Eigen Vectors are {} '.format(values,vectors))

## Output:
![mfai4](https://github.com/user-attachments/assets/71e6502b-8a0e-4e29-a000-e81f420e7822)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
