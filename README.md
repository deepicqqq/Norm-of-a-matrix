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
# Register No: 212223240024
# Developed By: DEEPIKA P
# 1-Norm of a Matrix

import numpy as np\
mat=np.array(eval(input()))\
ans=np.linalg.norm(mat,1)\
norm_of_matrix="{:.2f}".format(ans)\
print(norm_of_matrix)\

# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matri="{:.2f}".format(ans)
print(norm_of_matri)



# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)



```
## Output:
### 1-Norm of a Matrix
![Screenshot 2025-05-14 141926](https://github.com/user-attachments/assets/89b8cc98-5ccd-4628-a80c-b329038bd260)

### 2-Norm of a Matrix
![Screenshot 2025-05-14 142020](https://github.com/user-attachments/assets/8c06a345-cb37-4c50-a5ce-13d5309c7412)

### Infinity Norm of a Matrix
![Screenshot 2025-05-14 142052](https://github.com/user-attachments/assets/395a7436-d859-4cbe-9eae-11803e6b485f)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
