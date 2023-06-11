# Find the maximum of a list of numbers
## Aim:
To write a program to find the maximum of a list of numbers.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.	Get the list of marks as input
2.	Use the sort() function or max() function or use the for loop to find the maximum mark.
3.	Return the maximum value
## Program:

i)	# To find the maximum of marks using the list method sort.
```Python
''' 
Program to mark the maximum of marks using the list method sort
Developed by: Dhiyaneshwar
RegisterNumber: 212222110009
'''
def max_marks(list1):
    max = list1[0]
    for i in list1:
        if i > max:
           max = i
    return max



```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: Dhiyaneshwar P
RegisterNumber: 212222110009
'''
def max_marks(list1):
    max = list1[0]
    for i in list1:
        if i > max:
           max = i
    return max



```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: 
RegisterNumber: 
'''
def max_marks(list1):
    max = list1[0]
    for i in list1:
        if i > max:
           max = i
    return max



```
## Sample Input and Output
![image](https://github.com/Dhiyanesh24/FindMaximum/assets/118362288/a79ff02b-dcd7-4649-b0d7-46bb2c3b316a)
![image](https://github.com/Dhiyanesh24/FindMaximum/assets/118362288/792ad008-3d40-4a30-bdd8-206945034cdd)
![image](https://github.com/Dhiyanesh24/FindMaximum/assets/118362288/43a1ed97-418f-4634-9a3d-030c42f2c7b5)


## Output:

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
