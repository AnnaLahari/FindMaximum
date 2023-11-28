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
''' 
Program to mark the maximum of marks using the list method sort
Developed by: A.LAHARI
RegisterNumber:23002931 
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large



```

ii)	# To find the maximum marks using the list method max().
```
''' 
Program to find the maximum marks using the list method max().
Developed by: A.LAHARI
RegisterNumber: 23002931
'''
def max_marks(marks):
    marks.sort()
    res=marks[-1]
    return res



```

iii) # To find the maximum marks without using builtin functions.
```
''' 
Program to the maximum marks without using builtin functions.
Developed by: A.LAHARI
RegisterNumber: 23002931
'''
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max



```
## Sample Input and Output:
![image](https://github.com/AnnaLahari/FindMaximum/assets/149365425/741c15bf-25af-4c02-9134-c6d796b7e967)
![image](https://github.com/AnnaLahari/FindMaximum/assets/149365425/7adc80df-8f12-4b8e-9c0c-e58f68efead9)
![image](https://github.com/AnnaLahari/FindMaximum/assets/149365425/50520dcd-f97b-4b2c-af03-644a3803baea)



## Output:
![image](https://github.com/AnnaLahari/FindMaximum/assets/149365425/d753e44a-c7b7-41ff-b4ad-a72081d24a88)
![image](https://github.com/AnnaLahari/FindMaximum/assets/149365425/3f9e258c-4431-4fb4-8283-45b504f1ddbe)
![image](https://github.com/AnnaLahari/FindMaximum/assets/149365425/443cd169-33a2-4e75-905b-7fc1f739f7c9)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
