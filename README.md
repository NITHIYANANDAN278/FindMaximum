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
developed by: NITHIYANANDAN N
Register number:212222230099

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
![Screenshot 2024-04-08 144211](https://github.com/NITHIYANANDAN278/FindMaximum/assets/121784636/2ed04dee-e0e8-4d94-a13f-ca3fbe7c23cc)
![Screenshot 2024-04-08 144258](https://github.com/NITHIYANANDAN278/FindMaximum/assets/121784636/1b26b3fc-c6c4-4ac4-b9d3-ad3b1ce87568)
![Screenshot 2024-04-08 144409](https://github.com/NITHIYANANDAN278/FindMaximum/assets/121784636/98463697-9f99-4126-8359-693618db0289)





## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
