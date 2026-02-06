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
#Developed by:SARVESH.M
#RegisterNumber:212225240140


import numpy as np

A = np.array([[1, -3], [3, 1]])  
B = np.array([0, 10])  
solution = np.linalg.solve(A, B)

print(solution)
```
## Output:

<img width="1895" height="910" alt="Screenshot 2026-02-06 082225" src="https://github.com/user-attachments/assets/5a45629f-3376-4c5c-9a3d-06fc68e26ed6" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

