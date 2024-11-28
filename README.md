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
# Register No:24901151	
# Developed By:K S Vinay Suhirthan
# 1-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
a="{:.2f}".format(ans)
print(a)

# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
a="{:.2f}".format(ans)
print(a)

```
## Output:
### 1-Norm of a Matrix
![output 71](https://github.com/user-attachments/assets/811a8c42-1962-404f-a563-dbdeb6ca9632)

<br>
<br>
<br>

### 2-Norm of a Matrix
![output 72](https://github.com/user-attachments/assets/3cbcbd5d-19c4-4aa9-8bb3-73a278a5fa0c)

<br>
<br>
<br>

### Infinity Norm of a Matrix
![output 73](https://github.com/user-attachments/assets/08816b65-a12e-4120-bf4a-ef3daee699a8)

<br>
<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
