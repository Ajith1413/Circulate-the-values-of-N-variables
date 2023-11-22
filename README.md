# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Create a user defined function.
### Step 2: 
Get the variables from user to enter inside the list.
### Step 3: 
Get the value from the user for the number of rotation.
### Step 4: 
Using the slicing concept rotate the list.
### Step 5: 
After rotating the variables,store the rotated variables in 
a separate list.
### Step 6: 
At last,print the list of rotated variables.
## Program:
```
#Program to circulate N values.
#Developed by: AJITH KUMAR A
#RegisterNumber:23002150
def circulate():
    lst1=eval(input())
    n=int(input())
    lst2=lst1[n:]+lst1[:n]
    print("After circulating the values are:",lst2)
```

## Output:
![image](https://github.com/Ajith1413/Circulate-the-values-of-N-variables/assets/139842524/8e593f0a-3844-4d25-9659-23ccafac423e)


## Result:
The output for circulate the values of n variables is successfull.
