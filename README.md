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
Program to find the maximum mark
Developed by:JEECIKASRINA M
RegisterNumber:23013947
def max_marks(marks):
    sm=sorted(marks,reverse=True)
    max=sm[0]
    return max 
marks=list(input())

```

ii)	# To find the maximum marks using the list method max().
```Python
Program to find the maximum mark
Developed by:JEECIKASRINA M
RegisterNumber:23013947
def max_marks(marks):
    sm=max(marks)
    return sm 
marks=list(input())

```

iii) # To find the maximum marks without using builtin functions.
```Python
Program to find the maximum mark
Developed by:JEECIKASRINA M
RegisterNumber:23013947
def max_marks(marks):
    sm=max(marks)
    return sm 
marks=list(input())

```
## Sample Input and Output


## Output:
i)	# To find the maximum of marks using the list method sort.
![image](https://github.com/Jeecikasrina23013947/FindMaximum/assets/148515300/09390ff3-3f6f-4ff6-a6b5-8b7d90490345)
ii)	# To find the maximum marks using the list method max().
![image](https://github.com/Jeecikasrina23013947/FindMaximum/assets/148515300/a982a768-d10a-4b5e-9a3b-206aa90723f4)
iii) # To find the maximum marks without using builtin functions.
![image](https://github.com/Jeecikasrina23013947/FindMaximum/assets/148515300/f131a28f-f1ed-4e68-8b21-71a9711a600d)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
