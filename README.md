# Norm of a matrix
name:s.pooja abirami
212223100041
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
# Register No:212223100031
# Developed By:S.pooja abirami
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
![image](https://github.com/user-attachments/assets/96a1bb26-d9b5-4d56-8e3b-8aebec73b88a)

### 2-Norm of a Matrix
![image](https://github.com/user-attachments/assets/4d8e3aae-918e-4644-b894-aec614207425)


### Infinity Norm of a Matrix
![image](https://github.com/user-attachments/assets/477486e5-d0c6-45bc-8683-3d2eeafaf281)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
