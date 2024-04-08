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
```
Developed by: NITHIYANANDAN N
register number:212222230099
```

i)	# To find the maximum of marks using the list method sort.
```Python
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large



```

ii)	# To find the maximum marks using the list method max().
```Python
def max_marks(marks):
    large=max(marks)
    return large



```

iii) # To find the maximum marks without using builtin functions.
```Python
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>=max:
            max=i
    return max
    



```



## Output:
![image](https://github.com/drgbhuvaneswari/FindMaximum/assets/121784636/264b1765-faf4-4c6c-b7e2-3f3eab92f3ba)
![image](https://github.com/drgbhuvaneswari/FindMaximum/assets/121784636/4869dbc2-6541-484e-b71e-c8a596d95caa)
![image](https://github.com/drgbhuvaneswari/FindMaximum/assets/121784636/4a71ee6f-dab6-4266-b12d-5432890794c7)




## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
