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
Python
# Register No:24901064
# Developed By: BHARANI KUMAR.S
# 1-Norm of a Matrix
import numpy as np
arr=np.array(eval(input()))
result=np.linalg.norm(arr,1)
print(round(result))


# 2-Norm of a Matrix:
import numpy as np
arr=np.array(eval(input()))
result=np.linalg.norm(arr,2)
print(round(result,2))


# Infinity Norm of a Matrix:
import numpy as np
arr=np.array(eval(input()))
result=np.linalg.norm(arr,np.inf)
print(round(result))





## Output:
### 1-Norm of a Matrix
![Screenshot 2025-04-22 150415](https://github.com/user-attachments/assets/7d90619e-5603-4c74-b4f3-b6c4f76a5129)


### 2-Norm of a Matrix
![Screenshot 2025-04-22 150427](https://github.com/user-attachments/assets/b2b9a37f-911c-4ace-a6b1-29b7d51d0438)

### Infinity Norm of a Matrix
![Screenshot 2025-04-22 150439](https://github.com/user-attachments/assets/049780aa-ceb6-4111-8554-fab6e0df8fa4)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
