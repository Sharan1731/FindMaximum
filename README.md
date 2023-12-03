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
Developed by:Sharan.G
RegisterNumber:23002031
'''
def max_marks(marks):
    marks.sort()
    lar=marks[-1]
    return lar



```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by:Sharan.G
RegisterNumber:23002031
'''
def max_marks(marks):
    lar=max(marks)
    return lar




```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by:Sharan.G
RegisterNumber:23002031
'''
def max_marks(marks):
    lar=max(marks)
    return lar
    


```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:

![Screenshot 2023-12-03 164826](https://github.com/Sharan1731/FindMaximum/assets/144980172/53645362-de31-4bf6-b061-e9b9acecafe2)

![Screenshot 2023-12-03 164848](https://github.com/Sharan1731/FindMaximum/assets/144980172/595ff86f-e2d5-417b-a021-1707fa4467d5)

![Screenshot 2023-12-03 164907](https://github.com/Sharan1731/FindMaximum/assets/144980172/8f5e25de-22cb-479f-824b-e3183d258151)
Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
