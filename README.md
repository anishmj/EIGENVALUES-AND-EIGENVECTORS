# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Get the Matrix from the user.
### Step 2: Using the np.linalg.eig(),  we get two results (first is Eigenvalue and second is Eigenvector) of the given matrix.
### Step 3: Print the two results(Eigen values and Eigen Vectors)
### Step 4:End the Program
## Program:
~~~
import numpy as np
a=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vectors=np.linalg.eig(a)
print("Eigen values are",values,"and Eigen Vectors are",vectors)
~~~


## Output:
![GitHub Logo](/EIGEN.png)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
