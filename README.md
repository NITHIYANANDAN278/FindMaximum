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
def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return large



```

ii)	# To find the maximum marks using the list method max().
```Python
def max_marks(marks):
    large = max(marks)
    return large



```

iii) # To find the maximum marks without using builtin functions.
```Python
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max



```



## Output:
![Screenshot (27)](https://github.com/NITHIYANANDAN278/FindMaximum/assets/121784636/9d0b51dd-d8f9-4458-8a88-87c7e09cc690)
![Screenshot (28)](https://github.com/NITHIYANANDAN278/FindMaximum/assets/121784636/e97c51c8-50d7-46b8-9439-8e9158cd4f0d)
![Screenshot (29)](https://github.com/NITHIYANANDAN278/FindMaximum/assets/121784636/68c55ccb-76b1-4d65-8ade-e84020039bb4)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
