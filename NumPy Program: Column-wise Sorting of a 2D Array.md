## EX.No:5(B)	NumPy: Column-wise Sorting of a 2D Array
## AIM:
To write a NumPy program that sorts the elements in each column of a given 2D array in
ascending order.

## ALGORITHM:
Step 1:	Import Numpy Library.

Step 2:	Get 2D Numpy Array and new column value from the user.

Step 3:	Use the np.sort() function with axis=0 to sort the array column-wise.

Step 4:	Store the result in a new array.

Print the sorted array.

## PROGRAM:
```
import numpy as np
a=np.array(eval(input()))
print("Given array") print(end=" ")
print(a)
print()
print(np.sort(a,axis=0))
```
## OUTPUT:
 ![image](https://github.com/user-attachments/assets/ad73f6e2-2acc-4156-8749-82281a1faf1c)

## RESULT:
Thus the python program for sorting each column in numpy has been implemented and executed successfully.
