# Inverse-of-matrix

## AIM:
To write a python program to find the inverse of a matrix.

## ALGORITHM:
### Step 1:
Import Numpy module as np.

### Step 2:
Create empty lists.

### Step 3:
Get input from the user for number of rows and columns.

### Step 4:
Use nested lists to append list.

### Step 5:
Print the inverse of the array using np.linalg.inv

## PROGRAM:
```
'''
To find the inverse of a matrix
Developed By: S.Senthil Kumar
Register Number: 212221230091
'''


import numpy
rows=int(input())
columns=int(input())
l1=[]
for i in range(rows):
    temp=[]
    for j in range(columns):
        t=int(input())
        temp+=[t]
    l1+=[temp]
print(l1)
print(numpy.linalg.inv(l1))
```
## OUTPUT:

![Capture](https://user-images.githubusercontent.com/93860256/153715335-3836d411-aa10-4eaa-ac57-4a3091af0b5a.PNG)


## RESULT:
Thus, a program is written to find the inverse of the matrix.