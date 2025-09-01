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
```
#Program to find the solution for the given linear equations.
#Developed by:KARTHIK PADMANABAN R 
#RegisterNumber:212224110029

import numpy as np

A = np.array([[1, 3],
              [2, 5]])

B = np.array([5, -3])

solution = np.linalg.solve(A, B)
print(solution)   # [-34.  13.]
```
## Output:
<img width="1301" height="828" alt="Screenshot 2025-09-01 105925" src="https://github.com/user-attachments/assets/83c3d82f-7929-4516-87a7-1e08c05bf34f" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

