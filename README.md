# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
## Program:
```Python
# Register No: 212224240052
# Developed By: HARISH.S
# 1-Norm of a Matrix

import numpy as np
matrix = eval(input())
arr=np.array(matrix)
norm=np.linalg.norm(arr,1)
print("{:2f}".format(norm))



# 2-Norm of a Matrix

import numpy as np
matrix = eval(input())
arr=np.array(matrix)
norm=np.linalg.norm(arr,2)
print("{:.2f}".format(norm))



# Infinity Norm of a Matrix

import numpy as np
matrix = eval(input())
arr=np.array(matrix)
norm=np.linalg.norm(arr,np.inf)
print("{:.2f}".format(norm))


```
## Output:
### 1-Norm of a Matrix

<img width="574" height="628" alt="Screenshot 2025-11-18 092815" src="https://github.com/user-attachments/assets/10393156-fabd-4027-b13d-4047311043a3" />

### 2-Norm of a Matrix
<img width="592" height="662" alt="Screenshot 2025-11-18 092831" src="https://github.com/user-attachments/assets/af3e5320-1be1-4037-9bbc-7d4dd6cf0206" />


### Infinity Norm of a Matrix
<img width="484" height="591" alt="Screenshot 2025-11-18 092837" src="https://github.com/user-attachments/assets/5d59e224-8055-4878-860b-2b3a1b3af0a1" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
