# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:  Import the required library (numpy) in Python to perform matrix operations.
### Step 2:  Define the matrix for which the rank is to be calculated
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: Display the rank of the matrix as the output
## Program:
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A = np.array([[1, 2, 3],
              [3, 6, 9]])
rank = np.linalg.matrix_rank(A)
print(rank)
```
## Output:

<img width="1213" height="841" alt="image" src="https://github.com/user-attachments/assets/ec3dd5bd-3879-46db-9ee9-94ad529e5ec6" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

