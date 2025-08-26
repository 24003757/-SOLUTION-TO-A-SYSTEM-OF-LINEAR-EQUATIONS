# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## Aim:
To write a python program to find a solution to a system of linear equations.
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.solve(), we can find the solutions.
### Step 4: 
End the program
## Program:
#Program to find the solution for the given linear equations.
#Developed by: Vinolia Alaina . R
#RegisterNumber:212224240184
import numpy as np
A = np.array([[1, 3],[2, 5]])
B = np.array([5, -3])
le= np.linalg.solve(A, B)
print(le)

## Output:
<img width="1447" height="941" alt="Screenshot 2025-08-21 093730" src="https://github.com/user-attachments/assets/0dd358ef-2fcf-42ab-a4be-e9c1d22d45c3" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

