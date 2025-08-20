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
<img width="1243" height="159" alt="Screenshot 2025-08-20 111234" src="https://github.com/user-attachments/assets/1c0fff11-123e-47e1-805b-3c4475f4c06e" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

