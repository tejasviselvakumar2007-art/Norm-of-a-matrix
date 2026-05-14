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
# Register No: 212225040418
# Developed By: Sivasakthi S
# 1-Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
print("{:.2f}".format(ans))


# 2-Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
print("{:.2f}".format(ans))


# Infinity Norm of a Matrix


import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
print(f"{ans:.2f}")


```
## Output:
### 1-Norm of a Matrix
`<img width="1230" height="235" alt="image" src="https://github.com/user-attachments/assets/7984af6a-80c1-41e7-90e9-2c724b31014a" />

<br>
<br>
<br>

### 2-Norm of a Matrix
<img width="1224" height="279" alt="Screenshot 2026-05-14 181428" src="https://github.com/user-attachments/assets/4557428c-4b96-4c2e-960b-67e286182ea2" />


<br>
<br>
<br>

### Infinity Norm of a Matrix
<img width="1227" height="237" alt="image" src="https://github.com/user-attachments/assets/7bcba6a1-f1ac-414d-9254-4e0d28d89a1f" />

<br>
<br>
<br>

## Result

Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
