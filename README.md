# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each linear equations and assign in np.array()
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: End the program
## Program:
```
import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"   
import numpy as np
A = np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
B = np.linalg.matrix_rank(A)
print(B)
```
## Output:

<img width="1311" height="684" alt="{B347F38F-6477-427D-A94C-8C4A58FB8130}" src="https://github.com/user-attachments/assets/f9bc41f0-dbd8-4ea6-966a-34879b187c3e" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

