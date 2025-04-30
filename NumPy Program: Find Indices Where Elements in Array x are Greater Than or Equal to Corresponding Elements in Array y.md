## EX.NO:5(A)	NumPy: Find Indices Where Elements in Array x are Greater Than or Equal to Corresponding Elements in Array y

## AIM:
To write a NumPy program that finds The indices where elements in array x are greater than and equal to their corresponding elements in array y
## ALGORITHM
Step 1:	Import the NumPy library.

Step 2:	Define two NumPy arrays, x and y, of the same shape.

Step 3:	Use boolean indexing with comparison operators:

x > y gives a boolean array where the elements of x are greater than y.

x == y gives a boolean array where the elements of x are equal to y.

Step 4:	Use np.where() to get the indices where the conditions are satisfied.
Print the indices obtained from the comparisons.

## PROGRAM
```
import numpy as np
x=eval(input())
y=eval(input())
l1=np.array(x)
l2=np.array(y)
print(np.where(l1>l2))
print(np.where(l1==l2))
```
## OUTPUT:
![image](https://github.com/user-attachments/assets/09a89713-9ffe-4acc-a17d-e9586e7e7b32)

## RESULT:
Thus the python program for element wise comparison between two numpy array has been implemented and executed successfully.
