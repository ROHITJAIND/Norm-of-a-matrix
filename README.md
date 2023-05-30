# Norm of a matrix
## Aim:
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
- Hardware – PCs , Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1. Import numpy module
1. Get the input matrix using np.array()   
2. Find the norm of the matrix using np.linalg.norm()
   - np.linalg.norm(a,1) for 1-Norm
   - np.linalg.norm(a,2) for 2-Norm
   - np.linalg.norm(a,np.inf) for Infinity-Norm
3. Print the norm of the matrix in two decimal places.
## Program:
```
# Register No: 212222230120
# Developed By: ROHIT JAIN D
```
1-Norm of a Matrix:  
```
import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,1)
print("%.2f"%soln)
```  
2-Norm of a Matrix:
```
import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,2)
print("%.2f"%soln)
```  
Infinity Norm of a Matrix:
```
import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,np.inf)
print("%.2f"%soln)
```
## Output:
1-Norm of a Matrix  
![Screenshot 2023-04-25 192045](https://user-images.githubusercontent.com/118707073/234301432-5a3a4a8b-fed8-444a-b766-7dece61eab1c.png)

2-Norm of a Matrix  
![Screenshot 2023-04-25 192108](https://user-images.githubusercontent.com/118707073/234301457-cb6bb5b6-9507-471c-a8e3-22ee4e1d85cc.png)

Infinity Norm of a Matrix  
![Screenshot 2023-04-25 192115](https://user-images.githubusercontent.com/118707073/234301486-9f013859-2d74-4def-af23-a02b2cbc9791.png)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
