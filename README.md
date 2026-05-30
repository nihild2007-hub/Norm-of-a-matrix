# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
```
1. Get the input matrix using np.array()   
2. Find the 2-norm of the matrix using np.linalg.norm()
3. Print the norm of the matrix in two decimal places.
```
## Program:
```
# Register No: 212225040279
# Developed By: Nihil D
# 1-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"

import numpy as np
matrix = eval(input())

one_matrix = np.linalg.norm(matrix,1)
print(f"{one_matrix:.2f}")



# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: Nihil D
RegisterNumber: 212225040279
'''
import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"

import numpy as np
matrix = eval(input())
two_matrix = np.linalg.norm(matrix, 2)
print(f"{two_matrix:.2f}")



# Infinity Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"

import numpy as np
matrix = eval(input())
inf_matrix = np.linalg.norm(matrix,np.inf)
print(f"{inf_matrix:.2f}")


```

## Output:
### 1-Norm of a Matrix
<img width="1169" height="743" alt="{9E53EFA5-7B0E-49CC-85F1-18768CDDCB51}" src="https://github.com/user-attachments/assets/7dc033e7-1c9f-4c05-b59d-659ebb2e6923" />

### 2-Norm of a Matrix
<img width="1265" height="769" alt="{5789374A-6AD7-4D8A-8AF9-E2B96117AEA8}" src="https://github.com/user-attachments/assets/762c161c-98df-4448-9d9a-bc9d1b02c765" />


### Infinity Norm of a Matrix
<img width="1142" height="721" alt="{F45DE6A8-B705-450C-9BF3-6977A519EB62}" src="https://github.com/user-attachments/assets/905230c9-5cec-4e52-b00b-67527a44f9c4" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
