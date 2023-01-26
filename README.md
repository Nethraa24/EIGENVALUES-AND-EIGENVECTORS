# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
import numpy as np 
### Step 2: 
get input as a=np.array(eval(input())) 
###Step 3: 
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix. ###Step 4: 
print the eigenvectors and eigen values by the print statement

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by:J.NETHRAA
#RegisterNumber:22006789
import numpy as np
a=np.array([[2,2],[1,3]])
values,vectors=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```
## Output:
![image](https://user-images.githubusercontent.com/121215786/214869019-af51c4f9-997b-47df-8fda-c489cba9bbf8.png)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
