# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Give a user definded function as def circulate():
### Step 2: 
Give the value from the user for the number of rotation
### Step 3: 
Give a list with an array of certain numbers
### Step 4: 
using the slicing concept rotate the list
### Step 5: 
print the values
### Step 6: 
End the program
## Program:
```python
#Program to circulate N values.
#Developed by:V.S.Janani 
#RegisterNumber:22003192
def circulate():
    a=eval(input())
    n=int(input())
    a=a[n:]+a[:n]
    print("After circulating the values are: {}".format(a))
```
## Output:
![Screenshot from 2022-09-17 13-03-40](https://user-images.githubusercontent.com/113497333/190845995-0ad00d7e-cf1d-40b0-80ea-4d8429c8df5b.png)


## Result:
Thus the circulate n variables are successfuly executed


