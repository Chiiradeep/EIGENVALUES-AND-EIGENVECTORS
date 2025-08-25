# EIGENVALUES AND EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
tep 1: get the input from user

Step 2: import math and initialise the two values

Step 3: Using the np.linalg.eig(), we get two results (first is eigenvalue andsecond is eigenvector) of the given matrix.

## Program:
~~~
#Program to find the eigen values and eigen vectors.
#Developed by: Chiiradeep R
#RegisterNumber: 212224240028

import numpy as np

A = np.array([[2,2],
              [1,3]])


eigenvalues, eigenvectors = np.linalg.eig(A)


print("Eigen values are", eigenvalues,"and Eigen Vectors are",eigenvectors)
~~~

## Output:
<img width="1204" height="759" alt="image" src="https://github.com/user-attachments/assets/b66fbc87-f2c9-440f-865d-2d677991b779" />

<img width="1399" height="285" alt="Screenshot 2025-08-18 112726" src="https://github.com/user-attachments/assets/5ac25735-8a30-4a48-81e0-d20135882c66" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
