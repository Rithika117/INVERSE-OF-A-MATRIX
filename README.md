# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Step1 : import the numpy module to use the built-in function for calculation
Step 2: prepare the lists from each linear equations and assign in np.array()
Step 3: using the np.linalg.matrix_rank(),we can find the rank of the given matrix
Step 4: end the program
## Program:
#Program to find the inverse of a matrix.
#Developed by: Rithika k
#RegisterNumber:212224230230
import numpy as np
A= np.array([[2,1,1],[1,1,1],[1,-1,2]])
result = np.linalg.inv(A)
print(result)
## Output:
<img width="1897" height="1075" alt="image" src="https://github.com/user-attachments/assets/3a27ee9f-ebff-491e-8693-1c40ba2448a7" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

