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
# Register No:26003043
# Developed By:R S Sashwath
# 1-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=np.array(eval(input()))
norm1=np.linalg.norm(A,1)
norm="{:.2f}".format(norm1)
print(norm)



# 2-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=np.array(eval(input()))
norm1=np.linalg.norm(A,2)
norm="{:.2f}".format(norm1)
print(norm)



# Infinity Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=np.array(eval(input()))
norm1=np.linalg.norm(A,np.inf)
norm="{:2f}".format(norm1)
print(norm)




```
## Output:
### 1-Norm of a Matrix
<img width="562" height="195" alt="image" src="https://github.com/user-attachments/assets/61093673-8192-4551-9b6b-360e492ce5ce" />


### 2-Norm of a Matrix
<img width="507" height="250" alt="image" src="https://github.com/user-attachments/assets/d6258662-f3fd-4e13-b9a1-b23b77d80f48" />


### Infinity Norm of a Matrix
<img width="605" height="195" alt="image" src="https://github.com/user-attachments/assets/745bf02a-4a8d-45ff-b279-3845a733e410" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
