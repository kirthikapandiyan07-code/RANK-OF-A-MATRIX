# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:
Import the numpy module to use the built-in function for calculation.
### Step 2:
Prepare the lists from each linear equations and assign in np.array().
### Step 3:
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4:
End the program.

## Program:
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=np.array( [[5,-3,-10],[2,2,-3],[-3,-1,5]])
B=np.linalg.matrix_rank(a)
print(B)
```
## Output:

<img width="976" height="751" alt="image" src="https://github.com/user-attachments/assets/947e5838-8cc4-4e82-9a91-f10b188e1230" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

