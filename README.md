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
#Developed By: MARIO VIOFER J
#Register Number: 212223100032
# 1-Norm of a Matrix
import numpy as np
mat=eval(input())
a=np.linalg.norm(mat,1)
print("%0.2f"%a)



# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: MARIO VIOFER J
RegisterNumber: 212223100032
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_mat="{:.2f}".format(ans)
print(norm_mat)



# Infinity Norm of a Matrix
'''
Program to find the Infinity of a matrix 
Developed by: MARIO VIOFER J
RegisterNumber: 212223100032
'''
import numpy as np
mat=eval(input())
a=np.linalg.norm(mat,np.inf)
print("%0.2f"%a)




```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/Mario-Viofer-J/Norm-of-a-matrix/assets/144979232/e80ac836-3548-43dc-a0aa-cc5b1ccbe4ad)

### 2-Norm of a Matrix
![image](https://github.com/Mario-Viofer-J/Norm-of-a-matrix/assets/144979232/e9d20f4f-2fbd-4da2-bef3-50df40d584ed)

### Infinity Norm of a Matrix
![image](https://github.com/Mario-Viofer-J/Norm-of-a-matrix/assets/144979232/1e3bcb79-8f65-49a4-b215-5311c50d5c5c)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
