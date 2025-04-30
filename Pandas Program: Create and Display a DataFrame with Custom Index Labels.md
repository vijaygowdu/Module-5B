## EX.No:5(D)	Pandas: Create and Display a DataFrame with Custom Index Labels
## AIM
To create and display a DataFrame using the Pandas library in Python from a given dictionary and apply specific index labels to the rows.
## ALGORITHM
Step 1:Import the required libraries: pandas and numpy.

Step 2: Define a dictionary named exam_data containing keys such as 'name', 'score', 'attempts', and 'qualify'.

Step 3: Create a list called labels to be used as index labels for the DataFrame.

Step 4: Use the pd.DataFrame() function to create the DataFrame by passing the dictionary and the labels.

Step 5: Display the resulting DataFrame using the print() function or just typing the 

DataFrame name.
## PROGRAM:
```
import pandas as pd
import numpy as np
exam_data = {'name': ['Anastasia', 'Dima', 'Katherine', 'James', 'Emily', 'Michael', 'Matthew', 'Laura', 'Kevin', 'Jonas'],
    'score': [12.5, 9, 16.5, np.nan, 9, 20, 14.5, np.nan, 8, 19],
    'attempts': [1, 3, 2, 3, 2, 3, 1, 1, 2, 1],
    'qualify': ['yes', 'no', 'yes', 'no', 'no', 'yes', 'yes', 'no', 'no', 'yes']}
labels = ['a', 'b', 'c', 'd', 'e', 'f', 'g', 'h', 'i', 'j']
df = pd.DataFrame(exam_data , index=labels)
print(df)
```
## OUTPUT:
 
![image](https://github.com/user-attachments/assets/20282400-9894-41ab-98ef-96ccfabaacb8)


## RESULT:
Thus, the Python program has been created and executed successfully to create a DataFrame using the given dictionary and index labels and displayed.
