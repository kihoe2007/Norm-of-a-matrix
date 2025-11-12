
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
# Register No:212224230131
# Developed By:Kishore S M
## 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

## 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix

<img width="1180" height="1038" alt="image" src="https://github.com/user-attachments/assets/6e76c4e8-eb62-4c0e-98bf-0bb10b806ef2" />


### 2-Norm of a Matrix

<img width="1919" height="1145" alt="image" src="https://github.com/user-attachments/assets/9638f542-9af7-494f-a8c0-b9abef7b2135" />


<img width="1239" height="419" alt="image" src="https://github.com/user-attachments/assets/b2b5557b-fb15-437a-9e16-b9048870f138" />


### Infinity Norm of a Matrix

<img width="1287" height="918" alt="image" src="https://github.com/user-attachments/assets/bbb79b4e-086a-4cb5-bbed-5f54422ef352" />



## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
