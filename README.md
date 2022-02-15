# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
import the numpy module to use the built-in functions for calculation.
### Step 2: 
Prepare the lists from each inverse of matrix and assign in np.array().
### Step 3: 
Using the np.linalg.solve().we can find the solution.
### Step 4: 
End the program.
## Program:
~~~
#Program to find the inverse of a matrix.
#Developed by: deepika.j
#RegisterNumber:21005688
import numpy as np
A=np.array ([[1,0,3],[-1,2,-2],[2,3,-1]])
inverse=np.linalg.inv(A)
print(inverse)
~~~
## Output:
![output](.//IM.PNG)
## Result:
Thus the inverse of given matrix is successfully solved using python program.

