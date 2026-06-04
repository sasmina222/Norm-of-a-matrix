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
```
Program to find the 1-Norm of a matrix.
Developed by: SASMINA S
RegisterNumber: 212225230254
# 1-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np 
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_mat="{:.2f}".format(ans)
print(norm_of_mat)
# 2-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_mat="{:.2f}".format(ans)
print(norm_of_mat)
# Infinity Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,ord=np.inf)
norm_of_mat="{:.2f}".format(ans)
print(norm_of_mat)
```
## Output:
### 1-Norm of a Matrix

<img width="457" height="648" alt="image" src="https://github.com/user-attachments/assets/bf5f5617-5378-40b1-8b9d-fa1e3f9a8fd7" />

### 2-Norm of a Matrix

<img width="520" height="614" alt="image" src="https://github.com/user-attachments/assets/c4a05bc8-958d-4263-b6a3-9d0013cd6608" />

### Infinity Norm of a Matrix

<img width="536" height="550" alt="image" src="https://github.com/user-attachments/assets/79bdc2b4-581f-48d9-a3b6-75ed445caebf" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
./
