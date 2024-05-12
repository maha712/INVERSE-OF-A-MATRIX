# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.inv().we can find the solutions
### Step 4: 
End the program
## Program:

import numpy as np

a=np.array([[6,2,3],[3,1,1],[10,3,4]])

rank=np.linalg.inv(a)

print(rank)

## Output:
![Screenshot (367)](https://github.com/maha712/INVERSE-OF-A-MATRIX/assets/121156360/414ca728-b3f9-472c-8e70-58ba09dbc621)

## Result:
Thus the inverse of given matrix is successfully solved using python program

