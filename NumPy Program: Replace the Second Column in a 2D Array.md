## EX.No:5(C)	NumPy: Replace the Second Column in a 2D Array
## AIM
To write a NumPy program that deletes the second column from a given 2D array and
inserts a new column at the same position.

## ALGORITHM
Step 1:	Import Numpy Library.

Step 2:	Get 2D Numpy Array and new column value from the user.

Step 3:	Use np.delete() to remove the second column from the original array

Step 4:	Use np.insert() to insert the new column into the same position.

Print the final updated array.

## PROGRAM
```
import numpy as np
a=np.array(eval(input()))
b=np.array(eval(input()))
print("Printing Original array")
print(a)
print("Array after deleting column 2 on axis 1")
c=np.delete(a,1,axis=1)
print(c)
print("Array after inserting column 2 on axis 1")
print(np.insert(c,1,b,axis=1))
```
## OUTPUT
![image](https://github.com/user-attachments/assets/fd85124b-9fea-4904-ba84-f855e964eae2)

## RESULT
Thus the python program for replacing column in numpy has been implemented and executed successfully.
