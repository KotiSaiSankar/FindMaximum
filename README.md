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
Developed by: Koti Sai Sankar
RegisterNumber: 22001315
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
Developed by: Koti Sai Sankar
RegisterNumber: 22001315
'''
def max_marks(marks):
    large=max(marks)
    return large



```

iii) # To find the maximum marks without using builtin functions.
```
''' 
Program to the maximum marks without using builtin functions.
Developed by: Koti Sai Sankar
RegisterNumber: 22001315
'''
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max



```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![Screenshot from 2023-01-25 22-32-51](https://user-images.githubusercontent.com/118344248/214630475-28dd680f-bb28-44a6-bbe5-beb2c7e6a302.png)

![Screenshot from 2023-01-25 22-32-51](https://user-images.githubusercontent.com/118344248/214630594-ec11c59a-e9c2-495b-bf55-882afddb64ad.png)

![Screenshot from 2023-01-25 22-32-51](https://user-images.githubusercontent.com/118344248/214630637-ad48cda4-b480-408e-8b36-875fb252598c.png)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
