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
```
 Program to mark the maximum of marks using the list method sort
Developed by: DHARSAN KUMAR R
RegisterNumber: 23014208
def max_marks(marks):
    marks.sort()
    max=marks[0]
    for i in marks:
        if(i>max):
             max=i
    return max;
    



```

ii)	# To find the maximum marks using the list method max().
```
Program to find the maximum marks using the list method max().
Developed by: DHARSAN KUMAR R
RegisterNumber: 23014208

def max_marks(marks):
    return max(marks)



```

iii) # To find the maximum marks without using builtin functions.
```
Program to the maximum marks without using builtin functions.
Developed by: DHARSAN KUMAR R
RegisterNumber: 23014208

def max_marks(marks):
    max=0;
    for i in marks:
        if(i>max):
            max=i
    return max;
    



```
## Sample Input and Output


## Output:
![image](https://github.com/DHARSAN23014208/FindMaximum/assets/149365413/a1f1c859-2e0a-4e91-84bb-3753def080c0)
![image](https://github.com/DHARSAN23014208/FindMaximum/assets/149365413/7b75c00f-e711-46f3-8c10-c1af2b2b5fea)
![image](https://github.com/DHARSAN23014208/FindMaximum/assets/149365413/229be703-5ef0-4f5c-b4a6-0e80252c5420)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
