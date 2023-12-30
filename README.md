# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## step 1:
Get the input matrix using np.array()   
## step 2:
Find the 2-norm of the matrix using np.linalg.norm()
## step 3:
Print the norm of the matrix in two decimal places.
## Program:
```Python
# Register No:DURGA V
# Developed By:23013532
# 1-Norm of a Matrix

import numpy as np

mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)

# 2-Norm of a Matrix

import numpy as np

mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)



# Infinity Norm of a Matrix

import numpy as np

mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)





```
## Output:
### 1-Norm of a Matrix
![Alt text](<Screenshot 2023-12-30 190229.png>)
### 2-Norm of a Matrix
![Alt text](<Screenshot 2023-12-30 190258.png>)

### Infinity Norm of a Matrix
![Alt text](<Screenshot 2023-12-30 190310.png>)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
