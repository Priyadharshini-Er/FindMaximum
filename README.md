# Find the maximum of a list of numbers
## Aim:
To write a program to find the maximum of a list of numbers.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### STEP 1:
Get the list of marks as input
### STEP 2:	
Use the sort() function or max() function or use the for loop to find the maximum mark.
### STEP 3:
Return the maximum value
## Program:
i)	# To find the maximum of marks using the list method sort.
```Python
''' 
Program to mark the maximum of marks using the list method sort
Developed by: Priyadharshini.P
RegisterNumber: 22008758
'''
def max_marks(marks):
    marks.sort()
    return marks[-1]
```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: Priyadharshini.P
RegisterNumber: 22008758
'''
def max_marks(marks):
    return max(marks)
```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: Priyadharshini.P
RegisterNumber: 22008758
'''
def max_marks(list1):
    maximum=list1[0]
    for i in list1:
        if i>maximum:
            maximum=i
    return maximum
```
## Sample Input and Output
![output](./img/max_marks1.jpg) 
## Output:
![](./max1.png)
![](./max2.png)
![](./max3.png)
## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.