# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: mport the numpy module to use the built-in functions for calculation

###Step 2:
Prepare the lists from each linear equations and assign in np.array()

###Step 3:
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.

###Step 4:
End the program
 
## Program:
#Program to find the rank of a matrix.
#Developed by: rithika
#RegisterNumber:212225100038
```import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np

A = np.array([[1, 2, 3],
              [3, 6, 9]])

print(np.linalg.matrix_rank(A))
```
## Output:
<img width="1343" height="771" alt="Screenshot 2026-05-13 192711" src="https://github.com/user-attachments/assets/a9f50c1c-87dc-4386-a85e-7a790a36979d" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

