# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## Aim:
To write a python program to find a solution to a system of linear equations.
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Start.
1.Import the NumPy library.
2.Define matrix A containing the coefficients of the equations.
3.Define vector B containing the constants on the right-hand side.
4.Use np.linalg.solve(A, B) to find the solution vector C.
5.Print the values of C.
6.Stop.
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
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=[[1,3],[2,5]]
B=np.array([5,-3])
C=np.linalg.solve(A,B)
print(C)

```
## Output:
<img width="1039" height="593" alt="Screenshot 2026-05-28 135905" src="https://github.com/user-attachments/assets/7564bc50-6248-4f97-a90a-6905a1abdc84" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

