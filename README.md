# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import Required Library: Import the numpy library to use its array and linear algebra functionalities.
### Step 2: 
Create the Matrix: Define a 2D list or array with numerical values and convert it into a NumPy array using np.array().
### Step 3: 
Check Invertibility (optional but recommended): Ensure that the matrix is square (same number of rows and columns) and has a non-zero determinant, making it invertible.
### Step 4: 
Compute the Inverse: Use np.linalg.inv() to calculate the inverse of the matrix.
## Step 5:
Display the Result: Print the resulting inverse matrix using the print() function.

## Program:
```
#Developed by: Abishek P
#RegisterNumber: 212224240002
import numpy as np
a=np.array([[6,2,3],[3,1,1],[10,3,4]])
b=np.linalg.inv(a)
print(b)
```
## Output:
![image](https://github.com/user-attachments/assets/88a5c362-8e7a-43f3-bd15-027ede023b0a)

## Result:
Thus the inverse of given matrix is successfully solved using python program

