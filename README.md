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
Developed by: DILIP MP
Reg.no: 212223230048
'''
def max_marks(array):
    array.sort()
    return array[-1]
```
ii)	# To find the maximum marks using the list method max().
```
'''
Program to find the maximum marks using the list method max()
Developed by: DILIP MP
Reg.no: 212223230048
'''
def max_marks(array):
    return max(array)
```

iii) # To find the maximum marks without using builtin functions.
```
'''
Program to find the maximum marks without using builtin functions
Developed by: DILIP MP
Reg.no: 212223230048
'''
def max_marks(array):
    max1=array[0]
    for i in range(1,len(array)):
        if max1<array[i]:
            max1=array[i]
    return max1
```

## Output:
### To find the maximum of marks using the list method sort.
![py ex-06 1](https://github.com/DilipDofy/FindMaximum/assets/147223497/86a57e2c-d052-4a53-97b9-7a8d508ab7e2)

### To find the maximum marks using the list method max().
![py ex-06 2](https://github.com/DilipDofy/FindMaximum/assets/147223497/b73cea56-d0dd-4223-bcb1-aad77a084a60)

### To find the maximum marks without using builtin functions.
![py ex-06 3](https://github.com/DilipDofy/FindMaximum/assets/147223497/39a16130-6b9c-43a9-b37b-bb28ceadaf4d)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
