# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
Import numpy as np.
### Step 2: 
Assign np.linalg.eig()in eigen values and eigen vectors.
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
print both the values and vectors,then end the program.
## Program:
```python
#Program to find the eigen values and eigen vectors.
#Developed by:Suriya prakash.S
#RegisterNumber:23013599
import numpy as np
a=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
values,vector=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {} ".format(values,vector))
```
## Output:
![image](https://github.com/arulsuriyalokeshy/EIGENVALUES-AND-EIGENVECTORS/assets/149130151/6cc4826a-d48b-4476-b8a7-38b3e0645d55)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
