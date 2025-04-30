## EX.No:5(E)	Pandas: Join Two DataFrames Along Rows
## AIM:
To write a Python program using Pandas to join two DataFrames along rows (row-wise concatenation) and assign all data to a new DataFrame.

## ALGORITHM
1.	Import the required library pandas.

2.	Create the first DataFrame student_data1 using a dictionary.

3.	Create the second DataFrame student_data2 using a dictionary.

4.	Use the pd.concat() function to join both DataFrames along rows (axis=0).

5.	Display the combined DataFrame using print() or simply calling the DataFrame name.

## PROGRAM:
```
import pandas as pd

student_data1 = pd.DataFrame({ 'student_id': ['S1', 'S2', 'S3', 'S4', 'S5'],
'name': ['Danniella Fenton', 'Ryder Storey', 'Bryce Jensen', 'Ed Bernal', 'Kwame Morin'], 'marks': [200, 210, 190, 222, 199]})

student_data2 = pd.DataFrame({ 'student_id': ['S4', 'S5', 'S6', 'S7', 'S8'],
'name': ['Scarlette Fisher', 'Carla Williamson', 'Dante Morse', 'Kaiser William', 'Madeeha Preston'], 'marks': [201, 200, 198, 219, 201]})
print("Original DataFrames:")
print(student_data1)
print("________________________________")
print(student_data2)
print("\nJoin the said two dataframes along rows:")
result_data = pd.concat([student_data1, student_data2])
print(result_data)
```
## OUTPUT:  

![image](https://github.com/user-attachments/assets/a777f583-62f8-4334-a507-358deae75890)


![image](https://github.com/user-attachments/assets/495b0315-4015-435b-adf3-32b6fdc6b044)

## RESULT:
Thus, the Python program has been successfully created and executed successfully to join the two DataFrames row-wise using pd.concat() and all records from both DataFrames were included in the final output
