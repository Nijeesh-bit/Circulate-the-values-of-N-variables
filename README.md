# Circulate the values of N variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Create a function named circulate
### Step 2: 
Get the list values from the user
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
Print the rotated list
## Program:
```
#Program to circulate N values.
#Developed by: Nijeesh NJ
#RegisterNumber: 23010565

def circulate():
    l=eval(input())
    n=int(input())
    l=l[n:]+l[:n]
    print("After circulating the values are:",l)
```
## Output:
<img width="664" alt="image" src="https://github.com/Nijeesh-bit/Circulate-the-values-of-N-variables/assets/89188014/abfeea0c-128c-47bd-8526-b3c32e75c563">

## Result:
Thus successfully the array or list elements are rotated
