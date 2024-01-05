# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Step1:
Get the input matrix using np.array()   
## Step2:
Find the 2-norm of the matrix using np.linalg.norm()
## Step3:
Print the norm of the matrix in two decimal places.
## Program:
```Python
RegisterNumber: 23003613
Developed by: MOHAMED AAKIF ASRAR S

 1-Norm of a Matrix:
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
![Screenshot 2023-12-28 190513](https://github.com/MOHAMEDAAKIFASRAR/Norm-of-a-matrix/assets/148514683/a70c2e36-d4ca-4252-b2e3-944612717136)
### 2-Norm of a Matrix
![Screenshot 2023-12-28 190531](https://github.com/MOHAMEDAAKIFASRAR/Norm-of-a-matrix/assets/148514683/da1cebd5-b1c3-4682-aa77-3fa45710e5de)
### Infinity Norm of a Matrix
![Screenshot 2023-12-28 190540](https://github.com/MOHAMEDAAKIFASRAR/Norm-of-a-matrix/assets/148514683/7f056ad9-ee8f-4ae8-8ab4-baa79ac83883)
## Result
Thus the program for 1-norm,2-norm and infinity norm of a matrix are written and verified
 
