# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: import the numpy module to use the build in function in calculation.
### Step 2: prepare the lists from each linrar equation and assign in np.array()
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: end the program
## Program:
```
#Program to find the rank of a matrix.
#Developed by: SIVARANJANI M
#RegisterNumber: 212225220099

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=np.array( [[1,2,3],[3,6,9]])
solution=np.linalg.matrix_rank(a)
print(solution)
```
## Output:

<img width="1331" height="805" alt="Screenshot 2026-11-01 153302" src="https://github.com/user-attachments/assets/434a8224-a89e-4d40-85e4-52ff5ced26db" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

